# Privacy Policy for Hidden Automation Detector

**Last Updated**: December 2024

## Overview

Hidden Automation Detector ("the Extension") is committed to protecting your privacy. This privacy policy explains how we handle data when you use our Chrome extension for Salesforce automation visibility.

## Data Collection and Usage

### What We DO NOT Collect
- **Personal Information**: We do not collect, store, or transmit any personal information
- **Salesforce Data**: We do not store or transmit your Salesforce records or data
- **Analytics**: We do not use any analytics, tracking, or telemetry services
- **External Transmission**: All data processing happens locally in your browser

### What We DO Access
- **Authentication Tokens**: Temporarily stored in browser memory for API access
- **Debug Logs**: Retrieved from YOUR Salesforce org to show automation timelines
- **Salesforce Session**: Detected from browser cookies (like Salesforce Inspector)
- **User Preferences**: Extension settings stored locally in your browser

## Data Storage

### Local Storage Only
- Authentication tokens are encrypted and stored locally in your browser
- Extension preferences and settings remain on your device
- No data is sent to external servers or databases
- All data is deleted when you uninstall the extension

### Salesforce API Access
- The extension uses your existing Salesforce session
- API calls are made directly from your browser to your Salesforce org
- No intermediary servers or services are involved
- Standard Salesforce security policies apply

## Permissions Explanation

### Required Permissions
- **Host Permissions** (`*.salesforce.com`, `*.force.com`): Access your Salesforce org
- **Storage**: Store authentication tokens and preferences locally
- **Active Tab**: Detect record saves and display automation timelines
- **Clipboard Write**: Copy automation summaries when you click "Copy"

### Permission Usage
- Permissions are only used for stated functionality
- No background data collection or transmission
- No access to non-Salesforce websites
- No access to other browser tabs or activities

## Third-Party Services

### None Used
- No third-party analytics (Google Analytics, etc.)
- No crash reporting services
- No advertising networks
- No external APIs except Salesforce

## Data Security

### Security Measures
- OAuth 2.0 standard authentication
- Encrypted token storage using Chrome's storage API
- No plaintext credential storage
- Follows Chrome extension security best practices

### Salesforce Security
- Leverages Salesforce's built-in security model
- Requires same permissions as other Salesforce tools
- Subject to your org's security policies
- Sessions expire according to Salesforce settings

## Your Rights

### Data Control
- You can disconnect the extension at any time
- Uninstalling removes all local data
- No data recovery needed (nothing stored externally)
- Full control over when and how the extension is used

## Updates to Privacy Policy

We may update this privacy policy occasionally. Changes will be posted in the extension and on our repository. Continued use after changes indicates acceptance.

## Contact

For privacy questions or concerns:
- GitHub Issues: [Repository URL]
- Email: [Contact Email]

## Compliance

This extension is designed to comply with:
- Chrome Web Store Developer Program Policies
- General Data Protection Regulation (GDPR)
- California Consumer Privacy Act (CCPA)
- Salesforce security and privacy standards

---

**Summary**: We don't collect, store, or transmit your data. Everything stays in your browser and your Salesforce org. The extension works like other Salesforce developer tools (Inspector, etc.) but with a focus on automation visibility.
