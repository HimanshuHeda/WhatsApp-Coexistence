# WhatsApp Coexistence Setup

A web interface for setting up WhatsApp Business API coexistence with the WhatsApp Business app, allowing both to work on the same phone number.

## Overview

This tool helps connect an existing WhatsApp Business app number to the WhatsApp Cloud API, enabling "coexistence" where both the mobile app and API can operate on the same number simultaneously.

## Features

- Clean, modern dark theme interface
- Facebook/Meta authentication integration
- Real-time status updates during setup
- Automatic WABA and Phone Number ID extraction
- Error handling and user guidance

## Setup Instructions

This page uses Meta's official Embedded Signup SDK to facilitate the connection process. Users will:

1. Authenticate with their Meta/Facebook account
2. Select their business portfolio
3. Choose their WhatsApp Business Account
4. Opt for existing WhatsApp Business App number usage
5. Scan QR code from their mobile app
6. Complete the coexistence setup

## Technical Details

- **Facebook App ID**: 1469164717968670
- **SDK Version**: v22.0
- **Config ID**: 818095821311199
- **Session Info Version**: 2 (supports coexistence)

## Deployment

This is a static HTML page that can be deployed to any web hosting service including:
- GitHub Pages
- Netlify
- Vercel
- Any web server

## Security

- All authentication is handled by Meta's official SDK
- No third-party data collection
- Secure HTTPS required for Facebook SDK
- All communication happens directly with Facebook's servers

## Requirements

- WhatsApp Business App version 2.24.17 or higher
- Valid Meta/Facebook business account
- Existing WhatsApp Business Account in Meta Business Manager

## Live Demo

Visit: [Your GitHub Pages URL will be here]

## License

Copyright © 2026 Octodo Solutions