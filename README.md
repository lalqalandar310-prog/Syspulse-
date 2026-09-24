# 🛡️ SysPulse

**A lightweight Windows security monitor that sends you instant Telegram alerts.**

SysPulse sits quietly in the background of your Windows PC. It doesn't bother you, doesn't scan your files, and doesn't eat up your RAM. The moment something unusual happens, you know about it — straight to your phone.

[![Website](https://img.shields.io/badge/Website-syspulse.pro-blue)](https://syspulse.pro)
[![RAM](https://img.shields.io/badge/RAM-12--25%20MB-success)](https://syspulse.pro)
[![Price](https://img.shields.io/badge/Price-%2439%20one--time-green)](https://syspulse.pro)
[![Platform](https://img.shields.io/badge/Platform-Windows-lightgrey)](https://syspulse.pro)

---

## 💡 Kept lean on purpose

SysPulse is **not a bloated security suite**. It focuses on a few critical events and sends them straight to your phone. No feature creep, no cloud dashboards — just a quiet, dependable watchman.

We believe a security tool should be **invisible when you don't need it** and **responsive when you do**. That's why SysPulse typically uses around **12–25 MB of RAM** and focuses only on monitoring features that provide useful visibility into your Windows system.

No bloat. No ads. No distractions.

*Still here. Still silent. Still watching.*

---

## 🔍 What it actually does

- Detects **new processes** and shows their full file paths
- Detects **USB drives** being plugged in or removed
- Monitors **CPU, RAM, and Disk** usage
- Monitors **startup activity** and detects changes
- Sends **Telegram notifications** for monitored events
- Continues monitoring **locally** after license verification, even if the PC temporarily loses internet

No cloud dashboard. No unnecessary complexity. Just useful system activity alerts delivered to Telegram.

---

## 🎯 Where it fits

Think of SysPulse as a **lightweight Windows system activity monitor** with a security-focused approach.

- Something new runs on your PC? **You'll know.**
- A USB device is connected? **You'll receive an alert.**
- Startup activity changes? **SysPulse can notify you.**
- CPU, RAM, or Disk usage becomes unusually high? **You can be alerted.**

SysPulse is **not designed to replace antivirus software**. Instead, it provides additional visibility into system activity alongside your existing security tools.

---

## 📸 Screenshots

| SysPulse Running | Telegram Alert |
|------------------|----------------|
| [![SysPulse Running](telegram.jpg)](telegram.jpg) | [![Telegram Alert](telegram-alert.jpg)](telegram-alert.jpg) |

*(Click to enlarge)*

---

## ⚔️ SysPulse vs Traditional Antivirus

SysPulse and traditional antivirus software serve **different primary purposes**.

| Feature | SysPulse | Traditional Antivirus |
|---------|----------|----------------------|
| Primary focus | System activity monitoring | Malware detection |
| RAM Usage | ~12–25 MB | Usually higher |
| Telegram Alerts | ✅ Built-in | ❌ Not standard |
| Process Monitoring | ✅ Full path + name | ⚠️ Security-focused |
| USB Monitoring | ✅ Real-time alerts | ⚠️ Varies |
| Startup Monitoring | ✅ Detects changes | ⚠️ Varies |
| Configuration | Simple `config.ini` | Usually complex |

SysPulse is intended to **complement, not replace**, your antivirus.

---

## 🔬 SysPulse vs Process Explorer

We get asked this a lot. The short answer:

> **Process Explorer is your microscope. SysPulse is your guard dog.**

- **Process Explorer** — excellent for manual inspection
- **SysPulse** — designed for continuous background monitoring and notifications

They work well **together**.

Read the full comparison on [Dev.to →](https://dev.to/darkssel/syspulse-vs-process-explorer-two-windows-monitoring-tools-two-completely-different-philosophies-70l)

---

## 🚀 How to use it

1. Download the package from the [official website](https://syspulse.pro)
2. Open `config.ini` and enter your Telegram bot token, chat ID, and license key
3. Run `Run.bat`
4. To stop SysPulse, run `Kill.bat`

**No Python installation required.** Everything is compiled into a single `.exe`.

📖 **Detailed setup:** See the [Configuration Guide →](https://syspulse.pro/configuration)

---

## 📄 Documentation & Guides

Everything you need to understand and configure SysPulse:

### Getting Started
- [🏠 Homepage](https://syspulse.pro/) — Overview and features
- [⚙️ Configuration Guide](https://syspulse.pro/configuration) — Setup and customization
- [❓ FAQ](https://syspulse.pro/faq) — Common questions answered

### In-Depth Guides
- [🚀 Startup Monitor Guide](https://syspulse.pro/blog-startup-monitor) — How to monitor startup programs on Windows
- [🔌 USB Alert Guide](https://syspulse.pro/blog-usb-alert) — Detecting USB insertions in real time
- [🖥️ Process Monitor Guide](https://syspulse.pro/blog-process-monitor) — Monitoring new processes with Telegram alerts
- [📊 CPU/RAM Monitor Guide](https://syspulse.pro/blog-cpu-ram-monitor) — Detecting resource anomalies
- [⚔️ SysPulse vs Task Manager](https://syspulse.pro/blog-syspulse-vs-task-manager) — Why Task Manager isn't enough

### Legal
- [Privacy Policy](https://syspulse.pro/privacy)
- [Terms of Service](https://syspulse.pro/terms)

---

## 🔑 License & Activation

- **One license, one machine** (HWID-locked)
- The license is **verified automatically** when SysPulse starts
- **An active internet connection is required each time SysPulse is launched** for license verification — even if the license was successfully verified during a previous launch
- Once verification is complete, **SysPulse monitoring runs locally** on your PC
- Internet access is also required for **Telegram alerts** to be delivered
- Moving to a new PC? Contact [support](mailto:darkssel@proton.me) and we'll help you with the process

### 💰 Pricing
- **$39** one-time payment
- **Lifetime license** (HWID-bound)
- **No subscription**

[Purchase SysPulse →](https://syspulse.pro)

---

## 🔒 Privacy

SysPulse is designed to monitor **system metadata**, not personal files.

It monitors information such as:

- Process names and executable paths
- CPU, RAM, and Disk usage
- Startup activity
- USB events

**SysPulse does not inspect your personal files** or upload monitored system activity to a cloud dashboard.

Events are logged locally in a `syspulse.log` file.

After license verification, SysPulse monitoring runs **locally** on your PC. However, an internet connection is required when SysPulse starts (for license verification) and when Telegram alerts need to be delivered.

Your Telegram alerts are sent **directly to Telegram over HTTPS**.

---

## 📖 The story behind it

If you're curious about **why and how** I built this thing, I wrote a technical breakdown on Dev.to:

📝 [**I built a Windows security monitor that uses less RAM than your browser** →](https://dev.to/darkssel/i-built-a-windows-security-monitor-that-uses-less-RAM-than-your-browser-2kb1)

---

## 🔗 Related Projects

Other tools built by the same developer:

- **[GoImageKit](https://goimagekit.com)** — Free online image tools (compress, convert, resize, QR codes, JSON formatter, and more)
- **[CheatSheetHub](https://cheatsheethub.netlify.app)** — Developer cheat sheets (Git, Linux, Docker, SQL, Regex, and more)

---

## 🌐 Links

- **Website:** [https://syspulse.pro](https://syspulse.pro)
- **GitHub:** [SysPulse on GitHub](https://github.com/lalqalandar310-prog/Syspulse-)
- **Dev.to:** [SysPulse on Dev.to](https://dev.to/darkssel)
- **Medium:** [SysPulse on Medium](https://medium.com/@darkssel)
- **Product Hunt:** [SysPulse on Product Hunt](https://www.producthunt.com/products/syspulse)
- **AlternativeTo:** [SysPulse on AlternativeTo](https://alternativeto.net/software/syspulse/)
- **Support:** [darkssel@proton.me](mailto:darkssel@proton.me)

---

<p align="center">
  <strong>Made by Darkssel — a solo dev who wanted a quieter PC.</strong><br>
  <em>Stay aware. Stay secure. 🛡️</em>
</p>
