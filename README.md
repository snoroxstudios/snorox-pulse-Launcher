# Pulse Launcher
 
A small Windows app that installs, updates and starts **[Snorox Pulse](https://github.com/snoroxstudios/snorox-pulse)**.

Download the Launcher here: **https://github.com/snoroxstudios/snorox-pulse-Launcher/releases/tag/1.0.0fix**

It lists every Pulse version that exists on GitHub. Take the newest one, or go back to an older one if a new version doesn't sit right with you. One window, no hunting around for setup files.
 
<img width="1072" height="673" alt="image" src="https://github.com/user-attachments/assets/096d8c6f-3a29-4371-aff6-011d1806160a" />
 
## Download
 
**[Download Pulse-Launcher-setup.exe]** (always the latest version)
 
1. Run the setup. It installs for your user only, so no admin rights are needed.
2. Open **Pulse Launcher**.
3. Pick a version, click **Install**. Done.

### About the SmartScreen warning
 
Windows may say "Windows protected your PC" when you start the setup. That's because the launcher is not code-signed. A signing certificate costs real money and Snorox Studios is a one-person studio, so there is none (yet).
Click **More info**, then **Run anyway**.
 
## What it does

- **Shows all Pulse versions** from GitHub with date, download size and release notes. The newest stable one is marked, beta versions are marked as Beta.
- **Installs, updates or reinstalls** any version you pick. Going back to an older version asks you first, because your Pulse data might not run with an older build.
- **Checks every download** before it runs: file size, and SHA-256 whenever GitHub provides one.
- **Opens or uninstalls** Pulse for you.
- **Shows the real space Pulse uses** on your PC: the app, your settings and data, SPulse AI and the clip tool. The Pulse setup itself is small. The big parts (the AI model and FFmpeg for clips) are only downloaded when you switch them on inside Pulse, so the launcher shows both the download size per version and what is actually on your disk.
- **Works without internet** once it has loaded the list: it falls back to the last saved list so you can still see versions and notes.
- **Light and dark mode** (light by default, the sun/moon button switches).
- **6 languages:** Deutsch, English, 简体中文, 繁體中文, 日本語, 한국어. The launcher starts in your Windows language, and you can switch it any time.

## Privacy

The launcher talks to GitHub and nowhere else.
 
- No account, no telemetry, no tracking, nothing about you or your PC is sent anywhere.
- It only downloads from `https://github.com/snoroxstudios/snorox-pulse/releases` and refuses any other address.
- It only reads the size of Pulse's own folders to show the space used, and it never changes anything outside the Pulse install.
- No auto-start, no background service, no self-update. It runs when you open it.

## Requirements
 
- Windows 11
- Windows 10 would probably run but VERY BADLY in the view of performance
- Internet connection for the first start and for downloads.

## Good to know
 
- **Pulse updates itself too.** The launcher is for when you want to choose: a specific version, a rollback, or a clean reinstall.
- **"GitHub is slowing things down"** means GitHub's rate limit for anonymous requests was hit. Wait a few minutes and try again, the saved list stays usable meanwhile.
- **Uninstall** opens Pulse's own uninstaller. The launcher then waits and shows you when Pulse is gone.
 
## Support
 
Something broken, weird or missing? Open an issue here or write to snoroxstudios@gmail.com.
 
---
 
© Snorox Studios
