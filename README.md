# Meridian Music

Capture and develop your music in Obsidian — lyric fragments, hooks, full songs, ChordPro chord sheets, and demo recordings — from first spark to finished work. Mobile-first, no network, and everything is stored as plain Markdown notes so it syncs reliably through Obsidian Sync.

Runs fully standalone. If you also have the Meridian dashboard, it ships a read-only **Music** card that surfaces your unfinished works and lets you pull a recent recording straight back out.

## What it does

- **Capture, intentionally** — a fast modal (command, ribbon, or mobile toolbar) where you place the idea *as you save it*: what kind it is (lyric / hook / chord idea / melody / verse / note) and where it goes (a new scrap, attached to an existing work, or a brand-new work). Nothing needs re-sorting later. Optional title, optional inline audio.
- **Two note types** — **Works** (song / lyric / instrumental, with a status of spark → sketch → in-progress → done) and **Scraps** (timestamped orphan fragments you can later promote into a work or attach to one). Both are real Markdown notes with frontmatter, so they live in your vault and travel with your links.
- **Chord sheets** — write in ChordPro inside a fenced ` ```chordpro ` block; it renders as a clean lead sheet with chords aligned above the lyrics and an inline transpose control. Your source is never rewritten — transpose is view-only.
- **Audio** — record a voice memo straight into the capture modal, or attach an existing file. Recordings play inline, and you can reveal the underlying file to pull it back out without digging through the vault.
- **Catalog** — a browse view with search, status/type filters, an "unfinished only" toggle, and your most recent recordings surfaced up top.

## Install (BRAT)

1. Install the **BRAT** community plugin.
2. In BRAT: *Add beta plugin* → `SilentNinja06/music.obs`.
3. Enable **Meridian Music** in Community Plugins.

Development lives in the [obsidian-workspace monorepo](https://github.com/SilentNinja06/obsidian_workspace.obs) at `plugins/music`; releases are cut here for BRAT.
