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
- `offers.html` - Package offers and contact form
- `quote.html` - Request custom quotes
- `pay-invoice.html` - Pay invoices securely
- `track-project.html` - Check project status
- `success.html` - Payment success page

## Invoicing System
- **Request Quote**: `quote.html` - Forms submit to Formspree
- **Pay Invoice**: `pay-invoice.html` - Customers can pay using INV001 ($450), INV002 ($850), INV003 ($1500)
- **Track Project**: `track-project.html` - Check status with project codes (PROJ001, PROJ002, PROJ003, etc.)
- **Create Invoice**: Manually in Flutterwave dashboard, then share payment links

## Manual Invoice Creation
1. Log into Flutterwave dashboard
2. Create invoice with customer details
3. Copy payment link and send to customer
4. Customer can pay directly via the link

## Development
- Edit HTML/CSS/JS files directly
- Test locally by opening index.html in browser
- Commit changes to deploy automatically
