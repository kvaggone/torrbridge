# TorrBridge

Torrents download on a VPS you own. Your Mac talks only to that one machine, and
never opens a connection to a peer.

## Install

**1. Get a VPS and log in as root.** Any Ubuntu 22.04 or 24.04 server.

**2. Run this.** It installs the agent and prints one connection key.

```sh
curl -fsSL https://raw.githubusercontent.com/kvaggone/torrbridge-agent/main/install.sh | sudo bash
```

**3. [Download TorrBridge](https://github.com/kvaggone/torrbridge/releases/latest)**
and paste the key into it.

## What this repository is

Downloads only. The app is distributed here as a signed, notarised disk image;
its source is not public.

The server half is open source under MIT:
[torrbridge-agent](https://github.com/kvaggone/torrbridge-agent). You can read
every line of what you are about to run as root, which is the point.

## Requirements

macOS 14 or later. Universal for Apple Silicon and Intel.

A VPS with root access, 2 GB free disk plus room for what you download, and a
provider whose rules allow BitTorrent traffic.

---

© 2026 Arcane Gaming, Inc. All rights reserved.
