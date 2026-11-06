<div align="center">

# Tether

### Control any computer from anywhere — free, private, no account.

**A free alternative to AnyDesk + TeamViewer (remote desktop) and Termius (SSH), in one app.**
Watch a machine's live screen, drop into its terminal, touch‑control it from your phone,
and manage your servers over SSH — all peer‑to‑peer and end‑to‑end encrypted. No cloud in
the middle, no sign‑up, no seat pricing.

[![Download](https://img.shields.io/badge/⬇_Download-latest-62E88B?style=for-the-badge)](https://github.com/ggaryaman12/tether-releases/releases/latest)
&nbsp;
[![Open web app](https://img.shields.io/badge/🌐_Open_web_app-no_install-5B8CFF?style=for-the-badge)](https://web-gold-three-59.vercel.app)

![Release](https://img.shields.io/github/v/release/ggaryaman12/tether-releases?label=version&color=62E88B)
![Downloads](https://img.shields.io/github/downloads/ggaryaman12/tether-releases/total?color=5B8CFF)
![Platforms](https://img.shields.io/badge/platforms-macOS%20·%20Windows%20·%20Linux%20·%20Android%20·%20Web-8E8E96)
![Price](https://img.shields.io/badge/price-free-62E88B)
![E2E](https://img.shields.io/badge/encryption-end--to--end-62E88B)

</div>

---

## Download

| Platform | Get it | Notes |
|---|---|---|
| **macOS** | [tether-macos.dmg](https://github.com/ggaryaman12/tether-releases/releases/latest/download/tether-macos.dmg) | Apple Silicon + Intel. First open: **right‑click → Open** (see below). |
| **Windows** | [tether-windows-setup.exe](https://github.com/ggaryaman12/tether-releases/releases/latest/download/tether-windows-setup.exe) | Run the installer. |
| **Linux** | [tether-linux.tar.gz](https://github.com/ggaryaman12/tether-releases/releases/latest/download/tether-linux.tar.gz) | Extract and run `tether`. |
| **Android** | [tether-android.apk](https://github.com/ggaryaman12/tether-releases/releases/latest/download/tether-android.apk) | Allow "install unknown apps" once. |
| **iPhone / iPad** | **[Open the web app →](https://web-gold-three-59.vercel.app)** | No App Store needed — see iPhone below. |

**One‑line install (macOS / Linux):**

```bash
curl -fsSL https://tether-topaz-ten.vercel.app/install.sh | bash
```

This installs the app **and** clears the macOS security flag for you, so it just opens.
After the first install the app keeps itself up to date automatically.

---

## First open on each platform

### 🍎 macOS — one extra click the first time
Tether is a free, independent app and isn't paid‑notarized by Apple yet, so the very first
launch needs your OK (this is normal for indie apps — you only do it once):

1. Open the `.dmg` and drag **Tether** to **Applications**.
2. In **Applications**, **right‑click Tether → Open**, then click **Open** in the dialog.
   *(Double‑clicking shows "unidentified developer" and won't open — right‑click → Open is the trick.)*
3. If macOS still blocks it: **System Settings → Privacy & Security → scroll down → "Open Anyway."**

> Prefer the terminal? The one‑line install above does all of this for you.
> Technically: the app is signed ad‑hoc and this step clears the
> `com.apple.security.quarantine` flag. Your data never leaves your machine.

### 🪟 Windows
Run `tether-windows-setup.exe`. If SmartScreen appears, click **More info → Run anyway**
(again, because the app isn't paid‑code‑signed yet).

### 🐧 Linux
```bash
tar -xzf tether-linux.tar.gz && cd tether && ./tether
```

### 🤖 Android
Open the `.apk`, allow installing from this source once, and it installs.

### 📱 iPhone & iPad — use the web app (no App Store)
Tether runs fully in Safari — nothing to download:

1. Open **[web-gold-three-59.vercel.app](https://web-gold-three-59.vercel.app)** in Safari.
2. Tap **Share → Add to Home Screen**. It then opens full‑screen like a native app and
   updates itself automatically.

That's the intended iPhone experience — same remote screen, terminal, and touch control as the app.

---

## What you can do

- 🖥️ **Remote desktop** — live, hardware‑encoded screen of your Mac/PC on your phone, laptop, or browser.
- ✋ **Touch control** — drive a non‑touch computer by touch from your phone (and from a touchscreen laptop).
- ⌨️ **Full terminal** — a real shell with a best‑in‑class find (⌘F highlights every match, jumps between them).
- 🔑 **SSH servers cockpit** — connect, files, logs, services, a key vault — a free **Termius alternative**.
- 🔁 **One‑click Termius migration** — bring every host and SSH key over, decrypted locally. Nothing uploaded.
- 🤖 **Phone‑remote for AI coding agents** — watch Claude Code / Codex run and approve/steer it from anywhere.

## Why Tether

- **Free & no account.** No seats, no trials, no login.
- **Private by design.** Peer‑to‑peer **WebRTC (DTLS‑SRTP)**; the signaling server only introduces
  your devices and never sees your screen, keystrokes, or files.
- **Self‑hostable.** Point it at your own signaling server; no proprietary cloud.
- **Everywhere.** macOS, Windows, Linux, Android, and any browser.

## How it works

Your devices connect **directly** to each other over an encrypted WebRTC channel. A tiny
"blind" relay helps them find each other (exchanging connection info only) and then steps out
of the way. Screen video is hardware‑encoded; input travels on a low‑latency channel.

## FAQ

**Is it really free?** Yes. No account, no paywall.
**Is it safe?** Traffic is end‑to‑end encrypted and peer‑to‑peer; no server sees your content.
**AnyDesk / TeamViewer alternative?** Yes — remote screen + control, without the license.
**Termius alternative?** Yes — SSH cockpit + key vault, with one‑click migration from Termius.
**Does it auto‑update?** macOS/Windows update silently; Android updates in‑app; web is always latest.

---

<div align="center">

**Remote desktop · SSH client · screen sharing · touch control — free, private, open downloads.**

*AnyDesk alternative · TeamViewer alternative · Termius alternative · RustDesk‑style P2P · free remote access*

</div>
