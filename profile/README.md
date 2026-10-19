<div align="center">
  <img src="https://raw.githubusercontent.com/reachdevel/reachdevel.com/main/brand/social-preview.png" width="640" alt="reachdevel — personal software lab and engineering index">
</div>

# reachdevel

**Personal software lab and engineering index by [Levent Kurt](https://github.com/levent-kurt).**

Focused software built in the open — macOS utilities, self-hosted infrastructure and
developer tooling. Most projects are free and open source; a few are not, and each
repository states its own licence.

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

**OmniCast TV** — *closed source, internal testing*
Turns an Android TV into a wireless **AirPlay and DLNA receiver** for the phone and PC you
already own. Screen mirroring with sound, AirPlay audio, video-URL casting from Safari and
QuickTime, and UPnP pushes from VLC, BubbleUPnP and Plex. Local network only — no account,
no cloud, no tracking. Source is not published.

### Developer Tool

**[neotools](https://github.com/reachdevel/neotools)** · `Swift` · MIT
macOS-native replacements for `du`, `df`, `top`, `find`, `lsof`, `ps` and `rm` — twelve commands that
see **iCloud, APFS and the Trash**, an **Activity Monitor for the terminal** with performance and efficiency
cores, GPU and watts, and photo, video and document tools with nothing else to install. Script-safe: piped,
they print what the original prints. Installs with `brew install reachdevel/tap/neotools`.

**[trblocked](https://github.com/reachdevel/trblocked)** · `TypeScript` · MIT
Finds out **why a site will not open in Turkey** — DNS, IP, SNI or HTTP blocking, throttling, or the
site simply being down — by checking each layer against a control. Prints the court decision text
when the block page shows one. CLI and library on [npm](https://www.npmjs.com/package/trblocked),
no runtime dependencies.

**[MimeForge](https://github.com/reachdevel/mimeforge)** · `TypeScript` · MIT
File-type icons as **SVG**, generated from any file extension — one tiny (~1.3 KB), recolorable icon per type,
24 categories and ~1,365 known extensions. Colors, label font and icon bodies are swappable; CLI and library on
[npm](https://www.npmjs.com/package/mimeforge).

**[opencode-git-autocommit](https://github.com/reachdevel/opencode-git-autocommit)** · `TypeScript` · MIT
OpenCode **v2** plugin that commits your working tree when a session run reaches a terminal state —
succeeded, failed or interrupted — and derives the Conventional Commit subject from the staged diff.
No model call: the type and the file list come from `git diff --cached`, brand-new files included, and
commits are serialized per working directory. On [npm](https://www.npmjs.com/package/opencode-git-autocommit).

**[claude-git-autocommit](https://github.com/reachdevel/claude-git-autocommit)** · `TypeScript` · MIT
Claude Code **Stop hook** that commits your working tree when a turn ends — and always exits `0`, so a
failed commit never blocks the turn — with the same diff-derived Conventional Commit messages and no
model call. Installed with `npx claude-git-autocommit --user` or `--project`; the hook is
copied into `.claude/hooks` and `--dry-run` previews the change.
On [npm](https://www.npmjs.com/package/claude-git-autocommit).

---

## Elsewhere

- **Website** — <https://reachdevel.com>
- **Source of the site** — [reachdevel/reachdevel.com](https://github.com/reachdevel/reachdevel.com)

## About

Projects are listed newest-first on [reachdevel.com](https://reachdevel.com), which also
carries per-project installation steps. Releases are attached to individual repositories.

Licensing varies by project and is stated per repository — not everything here is open
source. Third-party ports and derivatives remain the property of their original authors.