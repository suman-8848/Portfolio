# Contact Form Setup Guide

Your portfolio website has a contact form that can be configured in two ways:

## Option 1: EmailJS (Recommended)

### Step 1: Sign up for EmailJS
1. Go to [EmailJS.com](https://www.emailjs.com/)
2. Create a free account
3. Verify your email address

### Step 2: Create an Email Service
1. In EmailJS dashboard, go to "Email Services"
2. Click "Add New Service"
3. Choose "Gmail" or "Outlook" (or your preferred email provider)
4. Connect your email account (sumanlamsal246@gmail.com)
5. Note down the **Service ID** (e.g., "service_abc123")

### Step 3: Create an Email Template
1. Go to "Email Templates"
2. Click "Create New Template"
3. Use this template:

**Subject:** New message from {{from_name}} - {{subject}}

**Body:**
```
Name: {{from_name}}
Email: {{from_email}}
Subject: {{subject}}

Message:
{{message}}
```

4. Save the template and note down the **Template ID** (e.g., "template_xyz789")

### Step 4: Get Your Public Key
1. Go to "Account" → "API Keys"
2. Copy your **Public Key** (e.g., "user_abc123")

### Step 5: Update the Code
Open `script.js` and replace these placeholders:

```javascript
// Line 95: Replace "YOUR_PUBLIC_KEY"
emailjs.init("user_abc123"); // Your actual public key

// Line 108: Replace "YOUR_SERVICE_ID" and "YOUR_TEMPLATE_ID"
emailjs.send('service_abc123', 'template_xyz789', templateParams)
```

## Option 2: Formspree (Alternative)

If you prefer Formspree:

1. Go to [Formspree.io](https://formspree.io/)
2. Create a free account
3. Create a new form
4. Get your form endpoint URL
5. Replace the contact form action in `index.html`:

```html
<form id="contactForm" action="https://formspree.io/f/YOUR_FORM_ID" method="POST">
```

## Option 3: Current Fallback

The form is currently set up with a fallback that opens the user's email client when EmailJS is not configured. This works immediately without any setup.

## Testing

1. After setup, test the form by filling it out and submitting
2. Check your email to confirm you receive the message
3. The form will show success/error notifications

## Troubleshooting

- **Form not sending**: Check browser console for errors
- **EmailJS errors**: Verify your Service ID, Template ID, and Public Key
- **No emails received**: Check spam folder and EmailJS dashboard

## Current Status

✅ Form validation is working
✅ Fallback email client option is working
✅ Success/error notifications are working
⏳ EmailJS configuration needed for direct email sending

Your contact form will work immediately with the fallback option, but for the best user experience, set up EmailJS following the steps above.
