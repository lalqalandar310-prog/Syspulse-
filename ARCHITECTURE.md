# SysPulse Architecture

SysPulse is a native Windows application built with Python
and compiled to a standalone EXE.

## Components

### Process Monitor
Uses Windows Management Instrumentation (WMI) to detect
new process creation events.

### USB Monitor
Watches removable drive events via WMI.

### Startup Monitor
Watches common Windows persistence locations:
- Registry Run keys (HKCU + HKLM)
- Startup folders (User + System)

### Resource Monitor
Uses psutil to track CPU, RAM, and disk usage.

### Telegram Bot
Formats event data and sends alerts via Telegram Bot API over HTTPS.

## Privacy Design

- No cloud dashboard
- No user data uploaded
- Local log file (syspulse.log)
- HWID-based licensing

## Technology Stack

- **Language**: Python 3.11+
- **WMI**: Windows event monitoring
- **psutil**: Resource tracking
- **requests**: Telegram API
- **pyinstaller**: EXE compilation
