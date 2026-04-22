# SpamPro Email Sender 2025

**SpamPro** is a powerful, feature-rich email sender built for **red teaming**, **spam testing**, **penetration testing**, and **bulk marketing**. Whether you're testing spam filters, simulating phishing attacks, or executing outreach campaigns at scale, SpamPro gives you advanced control, stealth features, and automation.

> **An active license is required to use SpamPro Email Sender.**
> [**BUY SpamPro Email Sender**](https://spamtools.org/product/spampro-email-sender-2025/)

---

# SpamPro Email Sender Features (v3.0.1)

## SpamTools AI Integration
- AI-powered content generation using SpamTools API
- **Campaign Designer** — generate complete campaigns (from-names, subjects, and full HTML email templates) in one click
- AI generates clean, deliverable, non-spammy content with proper spam filter avoidance
- AI button in every feature — From-Name Rotator, Subject Rotator, and Campaign Designer each have their own AI generate button
- Supports placeholder and spintax injection via AI when requested
- **AI Spam Checker** — analyze your email content for spam score (0-10 scale) with detailed warnings and suggestions
- Uses your existing SpamTools API key — no extra configuration needed

## Multi From-Name Rotation
- Add multiple sender display names and rotate them during sending
- Configure rotation interval (rotate after X emails sent)
- Supports placeholders ([@user], [@company], etc.) and spintax ({Option1|Option2}) inside from-names
- AI-powered from-name generation — describe what you need and AI creates professional sender names
- Add, remove, and manage from-names in a clean table UI
- Enable/disable with a single toggle

## Multi Subject Rotation
- Add multiple subject lines and rotate them during sending
- Configure rotation interval per campaign
- Supports all placeholders and spintax syntax
- AI-powered subject generation — describe your campaign and AI creates engaging, non-spammy subjects
- Add, remove, and manage subjects in a table UI
- Enable/disable with a single toggle

## Message Rotation System
- Add multiple email messages in settings
- Automatically rotate messages after X emails sent
- Configure individual send limits for each message
- Supports rich HTML and plain text messages
- Dynamic message switching for maximum deliverability
- Maintains natural sending behavior across large campaigns

## DKIM Signing
- Sign outgoing emails with DKIM for authentication and anti-spoofing
- Configure private key, selector, and domain
- Improves inbox placement and sender reputation
- Enable/disable with a toggle in the Deliverability tab

## List-Unsubscribe Headers (RFC 8058)
- Add one-click List-Unsubscribe headers to comply with RFC 8058
- Improves deliverability and sender trust with major providers
- Configure unsubscribe URL per campaign
- Enable/disable with a toggle in the Deliverability tab

## Spintax Engine
- Randomize email content per recipient using {option1|option2|option3} syntax
- Supports nested spintax: {Good {morning|evening}|Hello {there|friend}}
- Works in subject lines, from-names, and message bodies
- Each recipient gets a unique variation — helps avoid pattern detection

## Dynamic Personalization & Placeholders
- Email-based: [@email], [@user], [@domain], [@company], [@tld], [@project]
- Random/unique: [@md5], [@ranstr], [@rannum] — unique per recipient
- Date/time: [@date], [@time], [@datetime], [@timestamp], [@year], [@month], [@day], [@hour], [@minute], [@second], [@date_us], [@date_eu], [@time_12], [@weekday], [@month_name]
- Placeholders work in subjects, from-names, message bodies, and custom headers
- Combine with spintax for maximum variation

## Campaign Designer (AI-Powered)
- One-click complete campaign generation
- Describe your campaign goal and AI creates everything:
  - Multiple from-names (professional, varied, industry-matched)
  - Multiple subject lines (engaging, non-spammy, spam-filter safe)
  - Full HTML email template (inline CSS, table-based, email-client compatible)
- Choose what to generate: from-names only, subjects only, message body only, or all three
- Configure count for each (e.g., 5 from-names, 8 subjects)
- AI follows strict deliverability guidelines — avoids spam trigger words, uses proper structure
- Generated content auto-applies to the respective rotation tables

## Campaign Import & Export
- Export campaign settings to encrypted JSON file
- Import campaigns from file to quickly load configurations
- Exports include: from-names, subjects, message body, SMTP settings, headers, rotation config
- Email recipient lists are never included in exports for security
- Share campaign configurations between team members safely

## SMTP Rotation & Management
- Add multiple SMTPs and rotate them after X emails
- Dynamic SMTP row management with add/delete functionality
- Intelligent SMTP auto-configuration system
- Pre-made SMTP templates for faster setup
- Comprehensive connection fallback mechanism
- Smart port and SSL/TLS/STARTTLS auto-detection
- Built-in reconnect and retry logic
- Reduces chances of blacklisting and improves delivery

## Per-Domain Send Throttling
- Automatic rate limiting per recipient domain
- Predefined limits for major providers (Gmail: 50/hr, Yahoo: 30/hr, Outlook: 40/hr, etc.)
- Prevents rate-limit blocks and temporary bans
- Configurable limits per domain
- Enable/disable in settings

## Soft Bounce Retry
- Automatically retry emails that receive soft bounce (4xx) responses
- Configurable retry attempts and exponential backoff
- Distinguishes between soft bounces (temporary) and hard bounces (permanent)
- Enable/disable in settings

## SMTP Connection Health Monitoring
- Real-time monitoring of SMTP connection health
- Automatic failover to backup SMTP when primary degrades
- Periodic health checks during sending campaigns
- Detects degraded servers before they cause failures

## Session Tracking & Campaign Resumption
- Tracks which recipients have been sent to in each session
- Resume interrupted campaigns without re-sending to previous recipients
- Automatic session cleanup after completion
- Prevents duplicate sends after crashes or interruptions

## Multi-Threading
- Multi-threaded email sending for high throughput
- Enable/disable multi-threading per campaign
- Fast SMTP connection handling in parallel
- Safe and secure thread management

## Real-Time Bounce Checking
- Skip invalid/non-existent emails while sending
- Saves 80%+ time with automatic bounce skipping
- Powered by SpamTools Validation API
- Automatically checks each email before sending — skips bounced, sends valid
- Integrated Office365, GSuite, and Comcast email checkers
- Validation history with score tracking

## AI Spam Checker
- Analyze email content for spam score before sending
- AI-powered analysis using SpamTools API
- Score from 0-10 with detailed breakdown
- Identifies specific issues: spam trigger words, formatting problems, header issues
- Actionable suggestions to improve deliverability
- Check your email template before launching a campaign

## Email Checkers
- **Office365 Checker** — validate if Office365 email addresses exist
- **GSuite Checker** — validate Google Workspace email addresses
- **Comcast Checker** — validate Comcast email addresses
- Proxy support for all checkers
- Bulk checking with file import
- Real-time results with export capability

## Attachment Templates
- Supports HTML, TXT, DOC, PDF attachments
- Dynamic placeholders supported inside attachments
- Size validation (25MB limit)

## Custom Email Headers
- Configure custom headers (Reply-To, X-Priority, X-Mailer, etc.) with an easy-to-use dialog
- Smart header management — enable/disable custom headers with a simple toggle
- Visual status indicators in the dashboard
- Persistent settings saved between sessions
- Compatible with AWS SES, Gmail, Outlook, and all major SMTP providers

## Email Delay Control
- Fixed, random, or human-like email delays
- Helps avoid spam detection by mimicking human behavior
- Optimized timing for realistic sending patterns

## Proxy Support
- Add proxies manually or via file
- SOCKS proxy rotation (rotate/random modes)
- Rotate proxies after X emails using built-in proxy chain
- Proxy testing and validation
- Enhanced proxy handling for improved delivery and anonymity

## HTML Editor + Preview
- Rich text editor with formatting toolbar
- Add basic HTML with a single click
- Email preview — see how your message will look in the inbox
- Full preview window with rendered HTML
- Raw HTML source editing for advanced users

## Campaign Control
- Stop, Resume, and Pause controls for email tasks
- Real-time campaign management
- Track sending progress and status
- Live logs with detailed feedback during campaigns

## Theme System
- **Light Mode** — clean, professional light interface
- **Dark Mode** — fully dark UI for low-light environments
- **Mix Mode** — dark sidebar with light content area
- Live theme switching from the menu bar
- Windows DWM titlebar integration — titlebar matches the selected theme
- All dialogs and popups follow the active theme
- Responsive design — works on all screen sizes without text overlap

## Auto Updates + Version Control
- Automatic update checking on startup
- Manual update check from Help menu
- Download and install updates from within the app
- Version disable system — force updates for critical security fixes
- Skip versions — server-side control to skip updates for specific versions
- Backup and rollback support

## Multi-PC Compatibility
- Works across multiple systems with the same license
- License tied to your account, not your device
- 2-device limit with device fingerprinting

---

## Use Cases

| Use Case                         | Why Use SpamPro                          |
|----------------------------------|------------------------------------------|
| Red Team Phishing Simulations    | SMTP spoofing, realistic attachment drops|
| Spam Filter Testing              | Rotation, delay, personalization         |
| Bulk Email Marketing             | High throughput + delivery optimization  |
| Email Security Research          | Simulate and analyze real-world spam     |
| Deliverability Testing           | DKIM, List-Unsubscribe, spam score check |
| Campaign Management              | AI-powered content, multi-rotation       |

---

## How to Use

1. **Download the Tool**
   - GitHub: [https://github.com/spamtoolsorg/SpamPro](https://github.com/spamtoolsorg/SpamPro)

2. **Install & Launch**
   - Run the installer
   - Open SpamPro

3. **Activate License**
   - Enter your SpamTools license hash key
   - License verifies automatically

4. **Connect SpamTools API (Optional)**
   - Go to Settings > SpamTools API
   - Enter your API key from [spamtools.org/dashboard/apis](https://spamtools.org/dashboard/apis)
   - Unlocks: AI features, bounce validation, spam checking

5. **Load SMTPs and Lists**
   - Add multiple SMTPs manually or via file
   - Use pre-made SMTP templates for quick setup
   - Load email list (TXT/CSV)

6. **Configure Campaign Settings**
   - Set up from-name rotation, subject rotation, message rotation
   - Configure delay settings, proxy settings, and bounce checking
   - Add custom email headers
   - Enable DKIM and List-Unsubscribe for deliverability
   - Use the Campaign Designer to generate everything with AI

7. **Send Emails**
   - Hit send and track real-time progress
   - Monitor live logs, bounces, and SMTP rotation
   - Use Stop, Resume, and Pause controls as needed

---

## Video Tutorials

| Topic                             | Watch on YouTube |
|--------------------------------------|----------------------|
| How to Install SpamPro               | [Watch here](https://www.youtube.com/watch?v=EOTPlS6b4eM) |
| How to Activate SpamPro              | [Watch here](https://www.youtube.com/watch?v=C1JlLs7Kr4M) |
| Connect SMTP and Send Email         | [Watch here](https://www.youtube.com/watch?v=un80feBBsw0) |
| Use Multiple SMTPs + Rotation        | [Watch here](https://www.youtube.com/watch?v=uQC6dcPZUm0) |
| Stress Testing Emails                | [Watch here](https://www.youtube.com/watch?v=snWrEJKKu7o) |
| Enable Real-Time Bounce Validation   | [Watch here](https://www.youtube.com/watch?v=kDkB5y4fuQE) |

---

## License Required

SpamPro requires a **valid license** to unlock full functionality.

### How to Get a License:

- Buy from the official site:
  [https://spamtools.org/product/spampro-email-sender-2025/](https://spamtools.org/product/spampro-email-sender-2025/)

- Or contact support on Telegram:
  [https://t.me/spamtoolsorg](https://t.me/spamtoolsorg)

### License Notes:

- One license = multiple PCs (same user, 2-device limit)
- License linked to your SpamTools account

---

## Support

- Website: [https://spamtools.org](https://spamtools.org)
- Telegram Support: [https://t.me/spamtoolsorg](https://t.me/spamtoolsorg)
- Help Center: [https://spamtool.tawk.help](https://spamtool.tawk.help)
- Email: support@spamtools.org

---

## GitHub Repository

Repo: [https://github.com/spamtoolsorg/SpamPro](https://github.com/spamtoolsorg/SpamPro)

---

## Latest Updates - v3.0.1 (2026/03/28)

### New Features
- **SpamTools AI Integration** — AI-powered content generation for from-names, subjects, and email templates
- **Campaign Designer** — one-click complete campaign generation with AI
- **AI Spam Checker** — analyze email content for spam score with detailed suggestions
- **Multi From-Name Rotation** — multiple sender names with rotation and AI generation
- **Multi Subject Rotation** — multiple subject lines with rotation and AI generation
- **DKIM Signing** — email authentication with enable/disable toggle
- **List-Unsubscribe (RFC 8058)** — one-click unsubscribe headers for deliverability
- **Spintax Engine** — {option1|option2|option3} randomized content with nesting support
- **Per-Domain Throttling** — automatic rate limiting per recipient domain
- **Soft Bounce Retry** — automatic retry with exponential backoff
- **SMTP Connection Health Monitor** — real-time monitoring with automatic failover
- **Session Resumption** — resume interrupted campaigns without duplicate sends
- **Campaign Import/Export** — save and load campaign configurations (excludes email lists)
- **Theme System** — Light, Dark, and Mix themes with live switching and DWM titlebar integration
- **15+ Date/Time Placeholders** — [@date], [@weekday], [@month_name], [@time_12], [@timestamp], and more
- **Enhanced Email Validation** — MX lookup, disposable domain detection, typo suggestions

### Improvements
- Full dead code cleanup — removed all debug prints, commented code, and unused imports
- Codebase-wide import optimization for faster startup
- Improved UI responsiveness on all screen sizes
- Custom Nuitka-safe spinner widget (replaces broken QProgressBar marquee)
- Improved SMTP auto-detection and connection handling

### Previous Updates

#### v2.8.5 (2026/02/11)
- Improved email sending
- Clean trusted headers
- Fast performance
- Multi-API support
- Improved SMTP connections

#### v2.7.0 (2026/01)
- Message Rotation System
- Individual Message Limits
- Advanced Pattern Evasion
- Multi-Message Management

---

## Changelog

See the full history of updates [here](CHANGELOG.md).
