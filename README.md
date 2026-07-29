# WRJ Lookbook

A Windows desktop app for browsing and searching WRJ Design's interior photography
library — the firm's completed-project photography, searchable in plain language
instead of by folder name.

> **Internal tool.** Lookbook reads the firm's photography library over the WRJ
> network. Without access to it, the app will install but has nothing to show.
> This repository hosts the installer only; the source is private.

## What it does

- **Search in plain language** — "vaulted ceiling kitchen", "walnut vanity",
  "bathroom, sink". Photos are tagged by room, feature, material, and style, so you
  can search for what's *in* a photo rather than remembering which project it was.
- **Find similar photos** — pick any image, or drop in one of your own, and get the
  closest matches in the library.
- **Boards** — collect photos into a shared board for a project or a client
  conversation. Boards sync for the whole firm, and accept dropped-in images that
  aren't part of the library.
- **Stashes** — the same thing, kept private to your machine.
- **Client Projects** — browse the library by project, with notes and a per-project
  file area for documents.
- **Presentation mode** — show a board full-screen, without the interface.

## Install

1. Download the latest `WRJ Lookbook_<version>_x64-setup.exe` from the
   [**Releases**](https://github.com/hennerdenner/WRJ-Lookbook/releases/latest) page.
2. Run it. Windows will show **"Windows protected your PC"** — the installer isn't
   code-signed yet. Click **More info → Run anyway**. (See the note below.)
3. Launch **WRJ Lookbook** from the Start menu.

The first launch sets up its own configuration and downloads the library index, so
give it a minute before photos appear. Nothing else needs configuring.

### Requirements

- Windows 10 or 11, 64-bit
- Egnyte Drive installed and signed in, with access to the firm's photography folders
- About 1 GB of free disk space

### About that SmartScreen warning

The installer is not yet signed with a code-signing certificate, so Windows can't
verify the publisher and warns accordingly. The warning reflects the missing
signature, not anything detected in the file. If you'd rather not click through it,
ask for the installer to be handed to you directly instead.

## Updating

Download and run the newer installer over the top — your boards, stashes, and
settings are kept.

## Something not working?

Open an [issue](https://github.com/hennerdenner/WRJ-Lookbook/issues) or reach out
internally. Including what you searched for and what you expected helps a lot.
