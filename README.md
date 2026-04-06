# Proxy Manager

A simple GTK-based GUI tool to manage system proxy on Linux (APT, Git, environment).

## Screenshot

![Proxy Manager UI](screenshot.png)

## Features

- Enable / Disable proxy
- Session mode (no sudo)
- System-wide proxy (APT + Git)
- Proxy test (real IP detection)
- Notifications
- Saved profiles
- Restart apps option

## Installation

Download `.deb` from Releases and install:

sudo dpkg -i proxy-manager.deb

## Usage

Launch from application menu:
"Proxy Manager"

## Notes

- Session mode does NOT affect APT
- Proxy must be running 
