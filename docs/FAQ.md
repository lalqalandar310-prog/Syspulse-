# SysPulse FAQ

## General

### What is SysPulse?
SysPulse is a lightweight Windows security monitor that sends
real-time Telegram alerts for system events.

### Is it free?
No. SysPulse is $39 one-time with a lifetime license.
There's a 7-day money-back guarantee.

### Does it replace antivirus?
No. SysPulse complements antivirus software.

## Setup

### Do I need Python installed?
No. SysPulse is compiled to a standalone EXE.

### How do I get a Telegram bot token?
1. Open Telegram
2. Search @BotFather
3. Send /newbot
4. Follow instructions
5. Copy the token

### Where do I find my Chat ID?
1. Send a message to your bot
2. Visit: api.telegram.org/bot{TOKEN}/getUpdates
3. Find "chat":{"id":...}

## Usage

### How much RAM does it use?
Typically under 30 MB.

### Can I whitelist programs?
Yes. Add program names to config.ini whitelist.

### Does it work on Windows 7?
No. SysPulse requires Windows 10 or 11 (64-bit).
