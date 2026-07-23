# SysPulse

A lightweight Windows security monitor that sends you instant Telegram alerts.

SysPulse sits quietly in the background of your Windows PC. It doesn't bother you, doesn't scan your files, and doesn't eat up your RAM. The moment something unusual happens, you know about it — straight to your phone.

---

## 💡 Kept lean on purpose

SysPulse is not a bloated security suite. It focuses on a few critical events and sends them straight to your phone. No feature creep, no cloud dashboards — just a quiet, dependable watchman.

We believe a security tool should be invisible when you don't need it and lightning-fast when you do. That's why SysPulse stays under 30MB of RAM and never adds features that don't directly protect your machine. No bloat, no ads, no distractions. Just quiet, reliable monitoring.

---

## What it actually does

- New processes that suddenly appear (with their full file path)
- USB drives being plugged in or removed
- Windows Defender getting turned off
- CPU, RAM, or Disk usage going crazy

No cloud. No dashboard. Just a ping on Telegram when something smells fishy.

---

## Where it fits

Think of SysPulse as a lightweight Windows process monitor. Something runs on your PC? You'll know. A USB alert Telegram message pops up the second someone plugs in a flash drive. The whole thing is designed to be a super lightweight security tool — under 30MB of RAM, always. It even has a Windows startup checker that tells you when a program tries to hide in your boot sequence, and a Defender status monitor in case your antivirus decides to quit without telling you.

It's not here to replace your antivirus. It's here to watch the things your antivirus often misses.

---

## Screenshots

| SysPulse Running | Telegram Alert |
|------------------|----------------|
| [![SysPulse Running](telegram.jpg)](telegram.jpg) | [![Telegram Alert](telegram-alert.jpg)](telegram-alert.jpg) |

*(Click to enlarge)*

---

## SysPulse vs Traditional Antivirus

| Feature | SysPulse | Traditional Antivirus |
|---------|----------|----------------------|
| RAM Usage | ~30 MB | 200-600 MB+ |
| Telegram Alerts | ✅ Instant | ❌ Rarely |
| USB Detection | ✅ Yes | ❌ Usually missing |
| Process Monitoring | ✅ Full path + name | ⚠️ Limited |
| Startup Checker | ✅ Yes | ❌ No |
| Defender Status | ✅ Yes | ❌ No |
| Configuration | One config.ini file | Complex dashboards |

---

## How to use it

1. Download the package from the [official website](https://syspulse20.netlify.app).
2. Open `config.ini` — put your Telegram bot token, chat ID, and license key. (A guide is included in the download.)
3. Run `Run.bat`. To stop it, run `Kill.bat`.

No Python, no setup headaches. Everything's compiled into a single `.exe`.

---

## License & Activation

- One license, one machine (HWID-locked).
- Activates automatically the first time you run it with your key.
- Once active, the key can't be used elsewhere.
- Moving to a new PC? Shoot an email to [support](mailto:darkssel@proton.me) and we'll sort it out.

---

## Privacy

SysPulse does not look at your files. It only watches system metadata — process names, USB events, Windows Defender status. Nothing is collected, nothing is uploaded. Your alerts go directly to your Telegram over HTTPS.

---

## The story behind it

If you're curious about why and how I built this thing, I wrote a technical breakdown on Dev.to:  
[I built a Windows security monitor that uses less RAM than your browser](https://dev.to/darkssel/i-built-a-windows-security-monitor-that-uses-less-ram-than-your-browser-2kb1)

---

## Links

- Website: [syspulse20.netlify.app](https://syspulse20.netlify.app)
- Product Hunt: [SysPulse on Product Hunt](https://www.producthunt.com/products/syspulse)
- Support: [darkssel@proton.me](mailto:darkssel@proton.me)

---

*Made by Darkssel, a solo dev who wanted a quieter PC.*
