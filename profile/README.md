<div align="center">
  <img src="https://raw.githubusercontent.com/reachdevel/reachdevel.com/main/brand/social-preview.png" width="640" alt="reachdevel — personal software lab and engineering index">
</div>

# reachdevel

**Personal software lab and engineering index by [Levent Kurt](https://github.com/levent-kurt).**

Focused software built in the open — macOS utilities, self-hosted infrastructure and
developer tooling. Everything published here is free and open source.

**→ [reachdevel.com](https://reachdevel.com)**

---

## Projects

### macOS

**[Lidless](https://github.com/reachdevel/Lidless)** · `Swift` · MIT
Menu bar **Blackout Mode** — drives every connected display and the keyboard backlight to
dark, holds power assertions so the Mac never sleeps, and wakes on a keystroke or mouse
threshold. For overnight renders and builds in a dark room.

**[QBlocker4arm](https://github.com/reachdevel/qblocker4arm)** · `Swift`
Apple Silicon port of [QBlocker](https://github.com/steve228uk/QBlocker) — `⌘Q` is
swallowed until you hold it, so you quit an app on purpose instead of closing its window
by accident. No CocoaPods, no dependencies, `arm64` only.

### AI / Automation

**[Muninn](https://github.com/reachdevel/Muninn)** · `Python` · MIT
Self-hosted **stealth search and scrape gateway** for AI agents. One persistent,
anti-bot-hardened Chromium scrapes Google, Bing, DuckDuckGo and Mojeek behind a FastAPI
API, with engine rotation, quarantine, a SQLite TTL cache and a `/scrape` worker that
escalates to the browser only on a block challenge.

### Android TV

**[OmniCast TV](https://github.com/reachdevel) — internal testing** · `Kotlin` / `C++` · GPLv3
Turns an Android TV into a wireless **AirPlay and DLNA receiver** for the phone and PC you
already own. Screen mirroring with sound, AirPlay audio, video-URL casting from Safari and
QuickTime, and UPnP pushes from VLC, BubbleUPnP and Plex. Local network only — no account,
no cloud, no tracking.

### Developer Tool

**[opencode-git-commit](https://github.com/reachdevel/opencode-git-commit)** · `TypeScript` · MIT · *archived*
OpenCode plugin that commits your working tree when the session goes idle, using your last
assistant message as the commit message. Built for the **OpenCode v1.x** plugin API and
unmaintained since v2 changed that surface.

---

## Elsewhere

- **Website** — <https://reachdevel.com>
- **Source of the site** — [reachdevel/reachdevel.com](https://github.com/reachdevel/reachdevel.com)

## About

Projects are listed newest-first on [reachdevel.com](https://reachdevel.com), which also
carries per-project installation steps. Releases are attached to individual repositories.

Licensing varies by project and is stated per repository. Third-party ports and
derivatives remain the property of their original authors.