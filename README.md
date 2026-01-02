# webdevkv.github.io
About KV - Custom Web Development Services

## Features
- Responsive website with offers and packages
- Integrated invoicing system with Flutterwave
- Project tracking
- Quote requests

## Deployment
The site is deployed on GitHub Pages at https://webdevkv.github.io/

## Flutterwave Setup
- Public Key: Configured for live payments
- Client Secret: Used for manual invoice creation in Flutterwave dashboard
- Encryption Key: For secure API calls

## Pages
- `index.html` - Homepage
- `offers.html` - Package offers and contact form (not in navigation)
- `quote.html` - Request custom quotes
- `pay-invoice.html` - Pay predefined or custom invoices
- `generate-invoice.html` - Generate custom invoices for any business
- `track-project.html` - Check and update project status
- `success.html` - Payment success page

## Invoicing System
- **Request Quote**: `quote.html` - Forms submit to Formspree
- **Pay Invoice**: `pay-invoice.html` - Pay predefined or custom invoices with customer details
- **Generate Invoice**: `generate-invoice.html` - Create custom invoices for any business
- **Track Project**: `track-project.html` - Check and update project status (saved locally)
- **Create Invoice**: Use `generate-invoice.html` or manually in Flutterwave dashboard

## Manual Invoice Creation
1. Log into Flutterwave dashboard
2. Create invoice with customer details
3. Copy payment link and send to customer
4. Customer can pay directly via the link

## Development
- Edit HTML/CSS/JS files directly
- Test locally by opening index.html in browser
- Commit changes to deploy automatically
