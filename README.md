# Longvox for Mac

Press **F9** in any app, speak **English, Russian, or both**, and the text appears
where your cursor is. Optionally, Russian is translated into English while you
speak. Longvox also **records meetings**: you and the other side of a call,
turned into a transcript with speakers, a summary and action items.
Everything runs on your Mac: no account, no subscription, nothing you say
leaves the computer.

## Download

**[Download Longvox 0.2.22 for Mac](https://github.com/bigsov/longvox-app/raw/main/releases/0.2.22/Longvox-0.2.22.zip)**
(Apple silicon, macOS 15 or later)

SHA-256: `2989934d8a4d05f3348da4787b33c6054810d026f0f31a1386ab23739252c722`

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
| **⌃⌥M** | start or stop recording a meeting |
| **⌃⌥H** | mark this moment of the meeting being recorded |

The Longvox icon in the Dock or the menu bar opens Settings. There you can
change the key, the language (English + Russian automatic, English only,
Russian only), Accurate or Instant recognition, and Russian → English
translation.

## Meetings

- When a Zoom, Teams, Meet, FaceTime, Slack or other call starts, Longvox offers
  to record it, and can stop when the call ends. Or press **⌃⌥M**, or choose
  **Record a meeting** in the menu.
- It records your microphone and what the Mac plays (the other side of the
  call). macOS asks once for **System Audio Recording**.
- Afterwards: a transcript with **You** and **Others** (several voices on the
  call are told apart once the optional speaker-separation model is downloaded
  in Settings › Speech), a summary, key points and action items. Summaries are
  written by Apple Intelligence on Macs that have it; otherwise, and for
  Russian, Longvox picks the key sentences itself.
- The **Meetings** window (the list icon in the menu): search everything that
  was said, take notes, **Ask** a question about a meeting, play any moment,
  rename speakers, import an existing recording, and export to Markdown or
  subtitles.
- Optional: name meetings after the calendar event you are in, and save every
  meeting as a Markdown note in a folder you choose (an Obsidian vault, say).
- A meeting cut off by a crash or a power cut is finished at the next launch.

## Updates

Use **Check for Updates…** in Settings › About, or the **Updates** button in
the menu. Longvox downloads the new version from this page, checks its checksum
and signature, and relaunches. Your settings, words and history are kept.

## Privacy

Speech recognition runs on your Mac's GPU, and translation uses Apple's
on-device Translation framework. Meeting recordings, transcripts and summaries
stay on your Mac (and in your notes folder, if you choose one). Calendar
access, if you turn it on, is read on the Mac only. Longvox has no account and
uses no paid service. It connects to the internet only to download speech
models and to check this page for updates.
