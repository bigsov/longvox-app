# Longvox

## Downloads

| Platform | Download |
| --- | --- |
| Android phones | [Longvox Meet APK](https://github.com/bigsov/longvox-app/releases/latest/download/Longvox-Meet-Android.apk) |
| Windows 10 and 11, 64-bit | [Longvox Meet portable ZIP](https://github.com/bigsov/longvox-app/releases/latest/download/Longvox-Meet-Windows-x64.zip) |
| Mac with Apple silicon | [Mac downloads and installation](#install) |

On Android, open the APK and follow the installer. In Longvox, open **Meetings → Check for updates** for later releases. On Windows, extract the whole ZIP and open **Longvox.exe**. Windows saves calls in your Meetings library. For a group call, pair each device in Contacts and choose **Group video call** on Windows.

## Longvox for Mac

Press **F9** in any app, speak **English, Russian, or both**, and the text appears
where your cursor is. Optionally, Russian is translated into English while you
speak. Longvox also **records meetings**: you and the other side of a call,
turned into a transcript with speakers, a summary and action items. Speech
recognition, summaries and translation run on your Mac, with no account and no
paid service; you can also sync meetings with your paired devices (end-to-end
encrypted) and join private calls.

## Download

**[Download Longvox 0.2.27 for Mac](https://github.com/bigsov/longvox-app/raw/main/releases/0.2.27/Longvox-0.2.27.dmg)**
(Apple silicon, macOS 15 or later)

SHA-256: `ac913c915ea87a964d411cbae1a41d7846b40ec8cec480392b96f858e462be8e`

## Install

1. Open the downloaded **Longvox** disk image and drag **Longvox** onto
   **Applications**.
2. Open Longvox from Applications. macOS asks once whether to open an app
   downloaded from the internet: click **Open**. Longvox is signed with an
   Apple Developer ID, so there is no "Open Anyway" step in System Settings.
3. Follow the welcome window:
   - **Microphone**: click **Allow**.
   - **Accessibility**, so Longvox can type into other apps and F9 works
     without Fn. This is the one switch macOS asks you to turn on yourself:
     Longvox opens the right page, where it is already listed.
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

## Calls

- Join private one-to-one audio or video calls, or group video calls, with
  paired contacts on your private network or by invitation. Calls are hosted by
  **Longvox for Windows**.
- With the next Longvox for Windows (0.2.2 does not have these yet) you can also
  call one of your own devices directly, share a single window from this Mac
  during a call, and allow the other person to control it. Sharing and control
  are approved on this Mac for each session and can be stopped at any time.
  Window control is a preview.
- Window sharing needs **Screen Recording**; allowing control also needs
  **Accessibility** and **Input Monitoring** in System Settings.

## Updates

Use **Check for Updates…** in Settings › About, or the **Updates** button in
the menu. Longvox downloads the new version from this page, checks its checksum
and signature, and relaunches. Your settings, words and history are kept.

## Privacy

Speech recognition, meeting summaries and translation run on this Mac. Longvox
has no account and uses no paid service.

Longvox uses the network to download selected models and system language packs,
check for and download updates from GitHub, discover nearby devices, sync
meetings, recordings, voices and corrections with paired devices, and place
calls with contacts on your private network or join calls by invitation. Device
sync is end-to-end encrypted.

Calls with a Windows PC may be recorded by that PC, which tells you before you
join and while recording is active. If you turn on Calendar access, event
titles and invitees become meeting details that can sync with your paired
devices.
