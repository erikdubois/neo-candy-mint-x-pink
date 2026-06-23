# CLAUDE.md — neo-candy-mint-x-pink

## Project overview

Standalone repo for the **neo-candy-mint-x-pink** folder-icon theme — the same folder set as
`erikdubois/surfn-mint-x-pink` re-based onto the neo-candy-icons fallback.

## Current state

Ships one theme: `usr/share/icons/neo-candy-mint-x-pink/` — folders only. Packaged as `neo-candy-mint-x-pink-icons-git`
(recipe in `~/KIRO-PKG-BUILD-ICONS/neo-candy-mint-x-pink/`), `depends=('neo-candy-icons-git')`.

## Patterns & decisions

- Folders only; everything else inherits neo-candy-icons. `icon-theme.cache` gitignored.
  Payload reused verbatim from the Surfn counterpart; only Name/Inherits/dir name differ.
