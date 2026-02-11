# Changelog

All notable changes to SpamPro Email Sender will be documented in this file.


## [v2.8.5] - (2026/2/11) Latest
## 🚀 Improvements
- Improved email sending
- Clean trusted headers
- Fast performance
- Multi-API support
- Improved SMTP connections


## [v2.7.0] - January 2026

### ✨ New Features
- **Message Rotation System** - Add multiple email messages in settings with automatic rotation after X emails sent
- **Individual Message Limits** - Configure send limits for each message independently
- **Advanced Pattern Evasion** - Vary content across large campaigns to avoid spam filter detection
- **Multi-Message Management** - Perfect for huge lists and maintaining natural sending behavior

### 🔧 Improvements
- **Enhanced Campaign Control** - Better handling of multi-message campaigns
- **Improved Deliverability** - Dynamic message switching for maximum inbox placement
- **Persistent Message Settings** - All message rotation settings are saved and remembered between sessions
- **Optimized Message Queue** - Efficient handling of multiple message templates during bulk sends

### 📝 Notes
- Message rotation is ideal for large-scale campaigns with 10,000+ recipients
- Each message can have its own rotation limit (e.g., Message 1 sends 1000 times, then switches to Message 2)
- Supports all existing placeholders and dynamic personalization in rotated messages
- Works seamlessly with SMTP rotation and proxy rotation features



## v2.6.0 - December 2025

### New Features
- **Custom Email Headers** - Configure custom headers like Reply-To and more with an easy-to-use dialog
- **Enhanced Email Compatibility** - Improved support for AWS SES, Gmail, Outlook, and all major SMTP providers
- **Better Email Delivery** - Fixed duplicate header issues that caused emails to bounce

### Improvements
- **Smart Header Management** - Enable/disable custom headers with a simple toggle
- **Visual Status Indicators** - See your custom header status in the dashboard
- **Persistent Settings** - Custom headers are now saved and remembered between sessions
- **Port Auto-Detection** - Automatically uses the correct port and encryption for your SMTP server

### Bug Fixes
- Fixed "Duplicate header 'MIME-Version'" error with AWS SES and other strict SMTP servers
- Fixed port mismatch issues where wrong ports were being used
- Improved error messages for easier troubleshooting



## [2.5.0] - 2025-11-16 
### ✨ New Features
- Added **GSuite, Comcast, and enhanced Office email checkers**
- Added **Stop, Resume, and Pause controls** for email tasks
- Integrated **SpamTools** for seamless workflow
- Added **pre-made SMTP templates** for faster setup
- **Subject now supports placeholders** for dynamic email content
- Introduced a **more robust and modern application design**

### 🐞 Fixes & Improvements
- Fixed **proxy errors and app crashes**
- Improved **HTML email view and message body handling**
- Enhanced **email sending reliability and robustness**
- Optimized **SMTP connection timeout handling and connection speed**
- Reduced **connection retry overhead**


## [2.4.0] - 2025-09-18
### ✨ New Features
- Added **Office365 In-App Checker**
- Integrated **SpamTools** for seamless workflow
- Introduced a **more robust application design**

### 🐞 Fixes & Improvements
- Enhanced **message body handling**
- Improved **email sending reliability and robustness**



## [2.3.0] 
- Dynamic SMTP row management with add/delete functionality
- Intelligent SMTP auto-configuration system
- Comprehensive connection fallback mechanism
- Enhanced dark mode UI implementation
- Smart port and SSL detection
- Improved connection diagnostics
- Proxy Support
- Bounce Checking While Sending

### Fixed
- SMTP connection issues with non-standard configurations
- SSL/TLS handshake problems
- UI responsiveness issues in SMTP manager
- Port auto-detection logic
- Table row selection and deletion bugs

### Security
- Enhanced SSL/TLS connection validation
- Improved SMTP authentication security

### Performance
- Optimized SMTP connection timeout handling
- Faster connection establishment with intelligent port detection
- Reduced connection retry overhead

## [2.2.0] 
**Note:** This update is only available to users with an active license.

### New Features
- Proxy Support
- Bounce Checking while Sending

---

## [2.1.0]
### Added
- **Rich HTML Section** – Add basic HTML with a single click.
- **Email Preview** – See how your message will look in the inbox (click the 👁 icon).
- **Preview Window** – Opens a full preview in a new window.

### Improved
- Minor Bug Fixes – General stability improvements.
- Sending Enhancements – Faster and more reliable email delivery.
- SMTP Improvements – Better connection handling and performance.
- Multi-Computer Support – Now works across multiple systems.

---

## [1.1.0]
### Added / Improved
- Updated UI (Dark/Light modes)
- Added sending status (track how many emails are sent)
- SMTP rotation – add multiple SMTPs; messages are rotated to avoid limits or suspicions
- Email Delay – send emails with a human-like delay
- Other miscellaneous features and improvements
