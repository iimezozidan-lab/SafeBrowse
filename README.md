# SafeBrowse for Android

SafeBrowse is an open-source Android application that blocks unwanted websites at the system level using Android's Local VPN API.

## Features

- System-wide website blocking
- Local VPN (No external VPN servers)
- DNS filtering
- SNI inspection
- DoH / DoT support
- IPv6 protection
- Automatic blocklist updates
- Lightweight and battery friendly
- Privacy-first architecture
- Open source

## Requirements

- Android 8.0+
- VPN permission

## Installation

Download the latest APK from the Releases page.

## How it Works

SafeBrowse creates a local VPN service on your device. All DNS requests pass through the app where blocked domains are filtered before connections are established.

No browsing history is uploaded to external servers.

## Privacy

SafeBrowse processes traffic locally and is designed with user privacy in mind.

## License

MIT License
