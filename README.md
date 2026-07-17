# SysPulse

Lightweight Windows Security Monitor with Instant Telegram Alerts

SysPulse is a lightweight security monitor for Windows. It runs silently in the background and sends instant Telegram alerts when it detects unusual system activity.

### 📖 The Story Behind SysPulse

Ever wondered how to monitor system security without wasting your RAM? I've detailed the development journey, technical challenges, and how I optimized this monitor to be lighter than a browser tab in my latest article:

👉 [Read the full technical breakdown on dev.to](https://dev.to/darkssel/i-built-a-windows-security-monitor-that-uses-less-ram-than-your-browser-2kb1)

---

## Overview

Are you worried about hidden programs, malware, or unauthorized USB access on your PC?

SysPulse takes a different approach by focusing on real-time behavioral monitoring. It watches your system 24/7 and notifies you immediately when something unusual happens.

It is designed to be resource-efficient, using less than 30MB of RAM. It only monitors system metadata and processes; it does not read, access, or upload any of your personal files.

## Features

- Detects new or unknown processes and logs their full file path and process name
- Sends immediate alerts when a USB drive is connected
- Monitors Windows Defender status and alerts if it is disabled
- Tracks CPU, RAM, and Disk usage anomalies
- Sends optional daily security summaries to your phone

### Whitelist Management

SysPulse includes a flexible whitelist system to prevent false positives.

- Add or remove processes: edit the whitelist directly in `config.ini`
- Reset whitelist: a `reset_whitelist.bat` file is included

You can also customize alert thresholds, your Telegram bot token, chat ID, and monitoring intervals in `config.ini`.

## Screenshots

| Console View | Telegram Alert |
|:---:|:---:|
| [![Console View](telegram.jpg)](telegram.jpg) | [![Telegram Alert](telegram-alert.jpg)](telegram-alert.jpg) |

## How to Use

No Python installation is required. The core is compiled into a standalone executable.

1. Purchase a license and download the package.
2. Open `config.ini` and enter your Telegram Bot Token and License Key.
3. Run `Run.bat` to begin monitoring.
4. Use `Kill.bat` to safely terminate the application.

A detailed setup guide is included inside the downloaded ZIP file.

## Pricing

| | |
|---|---|
| Price | $39 (one-time payment, lifetime license) |
| Payment | Crypto (USDT / USDC) — instant delivery, no KYC) |
| Guarantee | 7-day money-back guarantee |

## Links

- 🌐 Official Website: [syspulse20.netlify.app](https://syspulse20.netlify.app)
- 🛒 Purchase SysPulse Pro: [Buy on Sellix](https://phantom.sellix.cx/p/syspulse-5)
- 📧 Support: [darkssel@proton.me](mailto:darkssel@proton.me)
- 🛡️ Now on [Product Hunt](https://www.producthunt.com/products/syspulse)

Built with Python for a lightweight and reliable footprint.
