# SysPulse

**Lightweight Windows Security Monitor → Instant Telegram Alerts**

SysPulse is a lightweight security monitor for Windows. It runs silently in the background and sends instant Telegram alerts when it detects unusual system activity.

---

## What is SysPulse?

SysPulse monitors your system in real time and alerts you via Telegram when:

- New or unknown processes appear (with full file paths)
- A USB drive is connected or removed
- Windows Defender is turned off
- CPU, RAM, or Disk usage becomes unusually high

No cloud dashboard. No heavy background services. Just important alerts sent directly to your phone.

---

## Screenshots

| Console View | Telegram Alert |
|--------------|----------------|
| [![Console View](console.jpg)](console.jpg) | [![Telegram Alert](telegram-alert.jpg)](telegram-alert.jpg) |

*(Click images to enlarge)*

---

## Why SysPulse?

| Feature | SysPulse | Traditional Antivirus |
|---------|----------|----------------------|
| RAM Usage | ~30 MB | 200–600 MB+ |
| Telegram Alerts | Instant | Rare |
| USB Detection | Yes | Often missing |
| Process Monitoring | Full path + name | Limited |
| Configuration | One `config.ini` file | Complex dashboards |

SysPulse is not a replacement for your antivirus. It works alongside it as a lightweight security watchdog that barks at the right moment.

---

## How to Use

1. Buy a license from [Sellix](https://phantom.sellix.cx/p/syspulse-5)
2. Extract the package and edit `config.ini` as described in the included README
3. Run `Run.bat` to start monitoring. To stop, run `Kill.bat`

No Python installation needed. Everything is compiled into a standalone executable.

*A detailed setup guide is included inside the purchased package.*

---

## License & Activation

- One license = one machine (HWID-locked)
- Automatic online activation on first run
- Once activated, the key cannot be used on another PC
- Need to transfer? Contact [support](mailto:darkssel@proton.me)

| Plan | Price | Payment | Guarantee |
|------|-------|---------|-----------|
| Lifetime | $39 | Crypto (USDT/USDC) via Sellix | 7-day money-back |

---

## Privacy

- No file content scanning — only process metadata and system events
- No data collection — everything stays local
- Alerts go directly to your Telegram via HTTPS

---

## Technical Story

Read how I built SysPulse and kept it under 30 MB:  
[I built a Windows security monitor that uses less RAM than your browser](https://dev.to/darkssel/i-built-a-windows-security-monitor-that-uses-less-ram-than-your-browser-2kb1)

---

## Links

- Website: [syspulse20.netlify.app](https://syspulse20.netlify.app)
- Purchase: [Sellix](https://phantom.sellix.cx/p/syspulse-5)
- Product Hunt: [SysPulse on Product Hunt](https://www.producthunt.com/products/syspulse)
- Support: [darkssel@proton.me](mailto:darkssel@proton.me)

---

*Made by Darksel*
