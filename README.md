# Email Signature Generator

A simple, single-page web application that generates professional HTML email signatures for fseDigital freelanceSEO team members.

## Features

- Clean, user-friendly interface
- Generates email-safe HTML signatures using tables and inline styles
- Compatible with Gmail, Outlook, and Apple Mail
- One-click copy to clipboard functionality
- Form validation to ensure all required fields are completed
- Professional design matching fseDigital brand guidelines

## How to Use

1. Open `index.html` in your web browser
2. Fill in your information:
   - **Photo URL**: Direct link to your profile photo (must be hosted online)
   - **Full Name**: Your complete name
   - **Job Title**: Your position at fseDigital
   - **Telephone Number**: Your contact phone number
   - **LinkedIn URL**: Your LinkedIn profile URL
3. Click **"Generate Signature"** to preview your signature
4. Click **"Copy HTML to Clipboard"** to copy the signature code
5. Paste the signature into your email client's signature settings

## Email Client Setup Instructions

### Gmail
1. Go to Settings → See all settings → General
2. Scroll to "Signature" section
3. Click "Create new" and give it a name
4. Paste the HTML code into the signature editor
5. Click "Save Changes" at the bottom

### Outlook (Web)
1. Go to Settings → View all Outlook settings → Compose and reply
2. Under "Email signature", paste the HTML code
3. Click "Save"

### Apple Mail
1. Go to Mail → Settings → Signatures
2. Click "+" to create a new signature
3. Paste the HTML code
4. Close settings (auto-saves)

## Image Hosting

The signature uses these hosted images:
- **Company Logo**: https://i.imgur.com/9KXqG5x.png
- **Partner Logos**: https://i.imgur.com/5xKvY2P.png

For your profile photo, you'll need to host your image online. Options include:
- Company website
- Imgur
- Google Drive (with public sharing enabled)
- Dropbox (with public link)

**Important**: Ensure your photo URL is a direct link to the image file (ending in .jpg, .png, etc.)

## Design Specifications

The signature includes:
- Circular profile photo (120px) with orange border (#FF9800)
- Name in large bold text (24px)
- Job title in gray text (13px, #888888)
- fseDigital freelanceSEO logo
- Blue horizontal divider (#1565C0)
- Phone number with icon
- LinkedIn URL (clickable link in blue #0077B5)
- Partner logos footer (Bing, Google Partner, Meta Business Partner, Yoast, Mailchimp)

## Technical Details

- Single HTML file with embedded CSS and JavaScript
- Uses HTML tables for maximum email client compatibility
- All signature styles are inline (no external CSS)
- Responsive design for the generator interface
- Client-side only - no server required

## Browser Support

The generator works in all modern browsers:
- Chrome
- Firefox
- Safari
- Edge

## License

Copyright © fseDigital freelanceSEO. All rights reserved.

## Support

For issues or questions, please contact your IT administrator.

---

**Note**: This tool generates HTML code. Make sure your email client supports HTML signatures before use.