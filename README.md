# channelBar CLI

The command-line interface for [channelBar](https://channelbar.app) - the menu bar for all occasions.

## About channelBar

channelBar is a macOS app that collects messages from various sources like MQTT, Webhooks, or the terminal and displays them in your menu bar. Create channels, connect providers, and keep everything in view.

## Why a CLI?

The CLI tool lets you integrate channelBar into your scripts, Git hooks, and automations. Send messages to your menu bar directly from the terminal without any network connection - the CLI communicates locally with the channelBar app on your Mac.

## Installation

### Homebrew (recommended)

```bash
brew tap code-bio/channelbar
brew install channelbar
```

Update:
```bash
brew upgrade channelbar
```

### PKG Installer

Download the latest `.pkg` file from the [Releases](https://github.com/code-bio/channelbar-cli-release/releases/latest) page and double-click to install.

### Verify Installation

```bash
channelbar version
```

## Requirements

- macOS 14.0 or later
- [channelBar app](https://apps.apple.com/app/channelbar/id6504863870) installed

## Privacy

The CLI processes data exclusively locally on your device. No usage data, telemetry, or analytics are transmitted to us or third parties. See the full [Privacy Policy](https://channelbar.app/privacy).

## Support

- Website: [channelbar.app](https://channelbar.app)
- Documentation: [channelbar.app/cli-tool](https://channelbar.app/cli-tool)
- Email: [support@channelbar.app](mailto:support@channelbar.app)

## License

Copyright 2026 code.bio GmbH. All rights reserved.
