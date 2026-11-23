# Corion 4.20 — Bug Sweep 2.0

> **4.20 is the last version of Corion on GitHub.** Starting with the next update, Corion won't be posted here anymore and this GitHub page will be made private, so these download links will stop working. New versions will be announced on [corion.space](https://corion.space). Corion 4.10 and 4.0 are retired; 4.20 installs over them and keeps your profile.

Corion 4.20 is a small update to the early Windows x64 release, shipped while Corion 5.0 (the Rust Engine) is built.

- Corion remembers fullscreen: if you left it in fullscreen (F11), it opens that way next time. Private windows never change or use this.
- A warmer start page: one Shield chip shows Shield's mode and how many requests it blocked this session, and opens Settings.
- Study shows research and library shortcuts under the search box; Customize opens the homepage panel directly.
- The early-build notice can be dismissed and stays dismissed on new tabs.
- Corion's own pages now use at least 12px text.
- The taskbar Jump List (Most visited, Recently closed, Recently visited and four Tasks) and the extensions manager were checked live and work.

## Install

Download Corion-4.20.0-win-x64-setup.exe and compare its SHA-256 with the accompanying checksum file. Windows 10/11 x64 is the target. Setup installs per user and can download missing Microsoft .NET 10 Desktop Runtime and Visual C++ prerequisites. Internet access is needed for those prerequisites. Close Corion before upgrading; existing profiles and settings are kept. Back up important profile data before installing development builds.

The installer is unsigned and Windows may display a reputation warning. Confirm the GitHub source and checksum before deciding whether to run it. Automatic update delivery is not configured; future updates must be downloaded manually. Remote crash/usage reporting is not deployed.

## Verification and limits

The automated test suites were run for this release, and the installer passed isolated install, upgrade, cancellation and uninstall checks with a sandboxed registration, plus the installer transaction safety checks. These checks do not establish compatibility with every Windows machine or website.

The Chrome Web Store link can stay dark for several seconds while the old store address redirects. DRM (for example full Spotify playback) and extension compatibility remain limited. No universal speed or memory reduction percentage is claimed.

This is an early release. Privacy and rights information describes actual behavior; it does not guarantee anonymity, universal blocking or worldwide legal compliance. The public repository contains the website, documentation and release assets; browser source remains private. Older release assets remain available.
