# Longvox for Mac

Press **F9** in any app, speak **English, Russian, or both**, and the text appears
where your cursor is. Optionally, Russian is translated into English while you
speak. Recognition and translation run on your Mac: no account, no
subscription, nothing you say leaves the computer.

## Download

**[Download Longvox 0.2.6 for Mac](https://github.com/bigsov/longvox-app/raw/main/releases/0.2.6/Longvox-0.2.6.zip)**
(Apple silicon, macOS 15 or later)

SHA-256: `937c410e2f4b087ac8fd47b6d62f9097ac234ae8c8d947558f461f58e108272c`

## Install

1. Open the downloaded zip, then drag **Longvox** into your **Applications** folder.
2. Open Longvox. This early version is not yet notarised by Apple, so the first
   time macOS says it cannot check the app. Open **System Settings › Privacy &
   Security**, scroll down, and click **Open Anyway** next to Longvox. You only
   do this once.
3. Follow the welcome window:
   - **Microphone** so Longvox can hear you.
   - **Accessibility** so it can type into other apps, and so F9 works without Fn.
   - **Speech models**: a one-time download of about 3 GB from Hugging Face,
     checked against published checksums.
4. Try it in the welcome window's "Try it here" box, then in any app.

## Using it

| | |
|---|---|
| **F9** (tap) | start dictating; tap again to stop and insert the text |
| **F9** (hold) | talk while held; let go to insert |
| **Esc** | cancel; nothing is typed |
| **⌃⌥V** | paste the last dictation again |

The Longvox icon in the Dock or the menu bar opens Settings. There you can
change the key, the language (English + Russian automatic, English only,
Russian only), Accurate or Instant recognition, and Russian → English
translation.

## Updates

Use **Check for Updates…** in Settings › About, or the **Updates** button in
the menu. Longvox downloads the new version from this page, checks its checksum
and signature, and relaunches. Your settings, words and history are kept.

## Privacy

Speech recognition runs on your Mac's GPU, and translation uses Apple's
on-device Translation framework. Longvox has no account and uses no paid
service. It connects to the internet only to download speech models and to
check this page for updates.
