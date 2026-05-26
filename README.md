![Visitor Count](https://visitor-badge.laobi.icu/badge?page_id=shimu-i/Nook)


# Nook
### A quiet reading companion for rainy afternoons

---

## What Is Nook?

Nook is a personal, offline-first reading and writing app for Android 8 and above. It is built for one person: you. It does not connect to the internet, show recommendations from strangers, push notifications, or ask you to follow anyone. It holds your books, tracks your reading, and gets out of your way.

The name says it all — a nook is a small, warm, tucked-away place. That is exactly how the app should feel.

---

## Who Is It For?

Nook is for readers who:

- Own PDF and EPUB files and want one calm, beautiful place to read them
- Find Goodreads cluttered and socially exhausting
- Want reading stats and progress tracking without a social feed attached
- Occasionally write notes, journals, or short pieces alongside their reading
- Care about typography, soft color, and distraction-free reading
- Want everything to work offline, always, with no login required

---

## Core Philosophy

**Local-first.** Your books stay on your device. Nothing is uploaded anywhere.

**Calm over clever.** No notifications that guilt you, no dopamine streaks that punish you, no algorithm deciding what you should read. Stats are there when you want them, invisible when you don't.

**Typography is the product.** A reading app that does not feel good to read in has already failed. Font, line spacing, and contrast are primary features, not buried settings.

**Fewer features, done warmly.** Nook does not compete on feature count. It competes on feel.

---

## Design Language

Nook's look is drawn from a single mood: a rainy afternoon with a warm drink and a good book.

**Color palette:**
- Background: warm parchment, soft linen — `#f0ede6`, `#e8e3d8`
- Accents: muted sage green, slate gray, dusty olive
- Text: deep warm brown, never cold black
- No bright colors, no neon, no saturated gradients

**Typography:**
- Reading content uses a serif face — Georgia, Literata, or Merriweather
- UI chrome uses a quiet sans-serif
- Headings are set in italic for warmth, not bold for authority

**Spacing:** Generous. Every element breathes. Nothing is crammed.

**Corners:** Soft and rounded throughout — no sharp edges anywhere.

**Animations:** Barely there. Transitions are slow and gentle, like turning a page.

**Mood reference:** Old libraries, worn paperbacks, handwritten marginalia, afternoon light through rain-streaked windows.

---

## How It Works

Five screens, always accessible from the bottom navigation bar:

| Tab | Purpose |
|-----|---------|
| Library | Browse all your imported books |
| Read | Open and read your current book |
| Write | Personal writing studio for drafts |
| Notes | All highlights and annotations across all books |
| Profile | Reading stats, yearly goal, app settings |

No discovery feed. No friends list. No internet.

---

## Home Screen Layout

```
 Nook
 Good evening, reader.        [7-day streak 🌿]

 ── Continue reading ──────────────────────────
  [cover]  The Design of Everyday Things
           Don Norman
           ████████████░░░░░░░  58%  [Resume]

 ── Want to read ──────────────────────────────
  [cover]  [cover]  [cover]  [cover]
  Meditations  Deep Work  Flow  Walden

 ── This month ────────────────────────────────
   4 Books    312 Pages    8h Reading

 ── From your notes ───────────────────────────
  "A person who never made a mistake never
   tried anything new."
   — your highlight · Meditations

 ─────────────────────────────────────────────
  Library   Read   Write   Notes   Profile
```

---

## Features

### Library

- Import PDF and EPUB files from device storage
- Batch import (many files at once)
- Automatic metadata detection: title, author, page count
- Smart cover detection from the first few pages of a PDF
- Manual cover selection: pick any page as the cover
- Upload a completely custom cover image
- Change the cover of any book at any time
- Shelves: Currently Reading, Want to Read, Finished, Favorites, DNF
- Create custom shelves with any name you choose
- Grid view (large warm covers) and compact list view
- Duplicate detection when importing the same file twice
- Book detail screen: cover, progress, last-read date, notes, highlights, tags, total reading time

### Reader

- Smooth vertical scroll and horizontal page-flip modes
- Opens instantly where you left off — every time
- Adjustable font size, line spacing, and margins (EPUB)
- Four reading themes: Parchment (default), Sepia, Dusk, Night
- In-reader brightness slider
- Keep screen awake while reading
- Focus mode: hides all UI, just the text
- Pinch to zoom (PDF)
- Thumbnail strip for quick page navigation
- Bookmarks
- Reading timer shown in the corner

### Highlights and Notes

- Long-press any text to highlight
- Four muted highlight colors (no neon)
- Attach a personal note to any highlight
- Save standalone quotes
- Export all notes from a book as plain text or markdown
- Notes tab shows every highlight across your whole library

### Writing Studio

- Distraction-free writing editor
- Chapter-based structure for longer writing
- Autosaves every 30 seconds
- Focus mode: full screen, no UI
- Typewriter mode: current line stays centered
- Reading preview: see how it looks as a finished page
- Everything stays private — nothing is ever published or shared
- Organize drafts into folders, add tags

### Stats and Yearly Goal

- Reading streak (days with at least one reading session)
- Pages and hours read this week, month, and year
- Yearly reading goal: set a book count, track quietly
- Per-book breakdown: sessions, total time, average session
- All stats are local — calculated from your sessions on-device

### Comfort Details

- Daily quote on the home screen drawn from your own highlights
- Mood tags on books (how you felt reading it)
- Parchment, Sepia, Dusk, and Night themes for different times of day
- Leaf icon for the streak (not a fire — calm, not urgent)

---

## Reading Themes

| Theme | Background | Text | Mood |
|-------|-----------|------|------|
| Parchment | Warm linen `#f0ede6` | Deep brown | Default, soft daylight |
| Sepia | Cream `#f5efe0` | Warm brown | Long reading sessions |
| Dusk | Warm gray `#3a3630` | Soft cream | Evening, low light |
| Night | Dark charcoal `#1e1c18` | Pale warm white | Dark room, OLED-friendly |

---

## What Nook Does Not Have

This is intentional and non-negotiable:

- No internet connection used or required
- No account, no login, no sign-up
- No social feed
- No push notifications
- No algorithm-driven recommendations
- No ads
- No in-app purchases
- No cloud upload
- No autoplay, trending shelf, or viral anything

---

## Supported File Formats

| Format | Status |
|--------|--------|
| PDF | Phase 1 |
| EPUB | Phase 1 |
| TXT | Phase 2 |
| MOBI | Future |

---

## Development Phases

### Phase 1 — The warm foundation
Library, PDF reader, EPUB reader, cover management, highlights and notes, reading stats, full theme system. This alone should feel complete, polished, and beautiful.

### Phase 2 — Writing studio
Distraction-free editor, chapter system, drafts, typewriter mode, folders.

### Phase 3 — Depth
Export options, mood tagging, reading calendar heatmap, yearly goal tracking.

### Phase 4 — Optional, subtle AI
Local-only features if added: chapter summaries, quote extraction, reading mood detection. Only if they remain quiet and non-intrusive.

---

## Technical Stack

| Component | Choice |
|-----------|--------|
| Language | Kotlin |
| UI | Jetpack Compose |
| PDF rendering | PDFium |
| EPUB parsing | custom or Folioreader |
| Database | Room |
| Image loading | Coil |
| Architecture | MVVM + Clean Architecture |
| Min Android | Android 8.0 (API 26) |
| Network | None |

---

## App Identity

> "A quiet corner for your books."

Not a Goodreads clone. Not a Wattpad clone. A warm, personal reading companion that feels like the app equivalent of a favourite armchair — familiar, unhurried, entirely yours.

---

*Project: Nook · Platform: Android 8+ · Connection: offline only · Version: 1.0 planning document*
