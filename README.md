# SysPulse

SysPulse is a lightweight security monitor for Windows. It runs silently in the background and sends instant Telegram alerts when it detects unusual system activity.

### 📖 The Story Behind SysPulse

Ever wondered how to monitor system security without wasting your RAM?
I've detailed the development journey, technical challenges, and how I optimized this monitor to be lighter than a browser tab in my latest article:

👉 [Read the full technical breakdown on Dev.to](https://dev.to/darkssel/i-built-a-windows-security-monitor-that-uses-less-ram-than-your-browser-2kb1)

---

## Overview

Are you worried about hidden programs, malware, or unauthorized USB access on your PC?

Traditional antivirus software relies on known signatures. SysPulse takes a different approach by focusing on real-time behavioral monitoring. It watches your system 24/7 and notifies you immediately when something unusual happens.

It is designed to be resource-efficient, using less than 30MB of RAM. It only monitors system metadata and processes; it does not read, access, or upload any of your personal files.

## Features

- Detects new or unknown processes and logs their full file paths
- Sends immediate alerts when a USB drive is connected
- Monitors Windows Defender status and alerts if it is disabled
- Tracks CPU, RAM, and Disk usage anomalies
- Sends optional daily security summaries to your phone

## Screenshots

| Console View | Telegram Alert |
|:---:|:---:|
| [![Console View](https://github.com/lalqalandar310-prog/Syspulse-/raw/main/telegram.jpg)](https://github.com/lalqalandar310-prog/Syspulse-/blob/main/telegram.jpg) | [![Telegram Alert](https://github.com/lalqalandar310-prog/Syspulse-/raw/main/telegram-alert.jpg)](https://github.com/lalqalandar310-prog/Syspulse-/blob/main/telegram-alert.jpg) |

## How to Use

No Python installation is required. The core is compiled into a standalone executable.

1. Purchase a license and download the package.
2. Open config.ini and enter your Telegram Bot Token and License Key.
3. Run Run.bat to begin monitoring.
4. Use Kill.bat to safely terminate the application.

A detailed setup guide is included inside the downloaded ZIP file.

## Pricing

| | |
|---|---|
| Price | $39 (one-time payment, lifetime license) |
| Payment | Crypto (USDT / USDC) |
| Guarantee | 7-day money-back guarantee — if SysPulse doesn't work as described, you get a full refund within 7 days |

## Links

- 🌐 Official Website: [syspulse20.netlify.app](https://syspulse20.netlify.app)
- 🛒 Purchase SysPulse Pro: [Buy on Sellix](https://phantom.sellix.cx/p/syspulse-5)
- 📧 Support: [darkssel@proton.me](mailto:darkssel@proton.me)
- 🛡️ Now on [Product Hunt](https://www.producthunt.com/products/syspulse)

Built with Python for a lightweight and reliable footprint.
