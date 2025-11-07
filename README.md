# Server Compass Releases

This repository contains **release binaries** for Server Compass, a desktop application for managing Virtual Private Servers (VPS).

**Note:** This repository contains only compiled binaries. The source code is maintained in a separate private repository.

---

## Download

### Latest Release

Download the latest version from the [Releases page](https://github.com/stoicsoft/server-compass-releases/releases).

### System Requirements

- **macOS:** 10.15 (Catalina) or later
- **Architectures:** Intel (x64) and Apple Silicon (arm64)

---

## Installation

### macOS

1. Download `Server-Compass-{version}.dmg` from [Releases](https://github.com/kai-builder/server-compass-releases/releases)
2. Open the DMG file
3. Drag "Server Compass" to your Applications folder
4. Launch Server Compass from Applications

### First Launch

On first launch, you may see a security warning. This is normal for apps distributed outside the Mac App Store:

1. Open System Settings → Privacy & Security
2. Look for "Server Compass" in the security section
3. Click "Open Anyway"

Or alternatively:
1. Right-click on Server Compass in Applications
2. Select "Open"
3. Click "Open" in the dialog

---

## What is Server Compass?

Server Compass is an offline-first desktop application that helps you:

- 🖥️ Manage multiple VPS instances from one place
- 📦 Deploy applications with one click
- 🗄️ Provision and manage databases
- 🔒 Securely store SSH credentials
- 📊 Monitor server metrics and health
- ⚙️ Manage cron jobs and scheduled tasks
- 🚀 Set up auto-deployments from Git repositories
- 🌐 Configure domains and SSL certificates

---

## Licensing

Server Compass offers:

### Free Trial
- 1 server
- 1 deployment
- 1 domain
- 5 cron jobs
- Limited command history (10 entries)

### Licensed Version
- Unlimited servers, deployments, and domains
- Unlimited cron jobs
- Full command history
- Auto-deploy functionality
- Database provisioning
- Data import/export (CSV)
- **12 months of automatic updates included**
- Email support

[Get a License →](https://servercompass.com)

---

## Automatic Updates

Licensed users with an active update subscription receive automatic updates:

1. App checks for updates automatically
2. Downloads in the background
3. Notifies when ready to install
4. Installs on restart

Updates are delivered through this releases repository.

---

## Support

- **Documentation:** [Coming soon]
- **Issues:** For bug reports and feature requests, please contact support
- **Email:** hello@stoicsoft.com

---

## Release Notes

See individual release pages for detailed changelogs and what's new in each version.

---

## Security

All releases are:
- ✅ Code-signed with Apple Developer ID
- ✅ Notarized by Apple
- ✅ Verified by macOS Gatekeeper

**Verify the signature:**
```bash
spctl -a -vvv -t install "/Applications/Server Compass.app"
```

Should show: `accepted` and `notarized`

---

## FAQ

**Q: Why is this a separate repository?**
A: To keep the source code private while making binaries publicly available for trial users and easy distribution.

**Q: How do I update the app?**
A: Licensed users receive automatic updates. Trial users can download the latest version manually from Releases.

**Q: Is my data secure?**
A: Yes! Server Compass is offline-first. All data (credentials, configurations) is stored locally on your machine and encrypted. Nothing is sent to external servers.

**Q: Can I use this commercially?**
A: Yes! The licensed version can be used for personal or commercial purposes.

**Q: What happens after 12 months?**
A: Your app continues to work forever, but you won't receive automatic updates. You can purchase an update renewal to continue receiving updates.

---

## Privacy

Server Compass does not collect any telemetry, analytics, or personal information. All server credentials and configurations are stored locally on your machine.

---

**Website:** [servercompass.app](https://servercompass.app)
**License:** Proprietary - Commercial use requires a license
**Copyright:** © 2025 Your Company Name

---

_This repository is for releases only. For source code access or contributions, please contact the maintainers._
