# Bluetooth Auto-Lock

Automatically locks your Windows PC when a selected Bluetooth device (e.g., your phone) disconnects.

## Features
  
- Monitors paired Bluetooth devices using Windows Runtime APIs
- Locks PC on device disconnect after configurable delay
- Minimizes to system tray with persistent background monitoring
- Supports dark theme only
- Autostart on Windows login

## Requirements

- Windows 10 or later
- [.NET 9.0 Desktop Runtime](https://dotnet.microsoft.com/en-us/download/dotnet/9.0) (or above)

## How to Add the App to Startup

- Press Win + R to open the Run dialog.
- Type shell:startup and hit Enter — this opens your Startup folder.
- Copy the app’s .exe file shortcut into that folder.
- Done — the app will now launch automatically when Windows starts.
