# Crucible Project Memory

Book Title: For the Promise

## Project Info
- **Title**: For the Promise
- **Series**: The Eōtria Saga, Book 2 (Book 1: *Riftmarked*)
- **Genre**: Epic Fantasy
- **Target**: TBD words
- **Current**: ~16,600 words — chapters 1-4 complete; chapter 5 written
  through the Council scene's opening line

## Current Status
- **Phase**: writing
- **Next up**: Chapter 5 Council confession beats, then Chapter 6
- **Story date**: 7th-9th of Ashenfall, 982 A.M. (see Flag #13 on the year)
- **Last Activity**: 2026-07-12

## Source Hierarchy (IMPORTANT)
1. **The manuscript** (`draft/chapters/`) — the author's prose; highest
   authority; never edit without instruction
2. **Author source docs** (`planning/source-*.md`) — character sheets,
   worldbuilding compendium, races, Book 1 sample, roadmap
3. **Derived docs** (constellation bible, world forge, strand maps, outlines,
   story bible) — reconciled summaries; markers: **[PROPOSED]** = assistant
   suggestion, **[TBD]** = needs author, **[FLAG]** = contradiction between
   sources (full list: `planning/constellation-bible.md` → Continuity Flags)

## Project Rules
- Never invent characters not in the Constellation Bible / source sheets
- Never create plot points not in the outline
- Verify against story bible + style profile before writing
- Flag `[INVENTED: description]` for any invented details
- Honor the author's standing rules (e.g. both moons — Luuna and Sol, one
  visibly shattered and brighter — in every night scene)
- Book 2 series constraint: the five-year countdown to Elyrieth stays silent;
  the awakening belongs to Book 3

## Commands
- `/crucible-suite:crucible-status` - Check progress
- `/crucible-suite:crucible-continue` - Resume from any phase
- `/crucible-suite:crucible-write` - Draft prose
- `/crucible-suite:crucible-edit` - Revise manuscript
- `/crucible-suite:crucible-review` - Trigger manual review
- `/crucible-suite:crucible-restore` - Restore from backup

## Recent Decisions
- Manuscript (5 chapters) ingested and split into draft/chapters/
- Style profile captured (style-profile.json) from Book 2 prose + Book 1 sample
- All planning docs reconciled against character sheets + worldbuilding
  compendium; Dark Mirror resolved as the Order's canon foil web
- Canon resolutions: Archwarden = Rhen Tauvor; Council of Twelve; Caer Seryth
  in Halreth's Vespur Plains; Nullbrand is Brunor's

## Open Questions (author input needed)
- **Flag #13**: Book 2's year — manuscript says 982 A.M.; compendium says
  983-985
- Ch 1 "Telvor" → Tauvor (one-word prose fix, author's call to make)
- Damien's unheard rain-words to Elaine — planned reveal point?
- What exactly the Promise "lost" in the siege ("to lose the rift...")
- What Mark (Revanius?) turned out to be, and when the reader learns it
- Chapter count / target length; which pressure recedes during the Scattering
- Full flag list: planning/constellation-bible.md → Continuity Flags (15)

---

> **How Context Works**: This root CLAUDE.md loads at session start.
> Subdirectory CLAUDE.md files (in `planning/`, `outline/`, `draft/`) load
> lazily when Claude reads files in those directories. The story bible and
> style profile are queried on-demand, not auto-loaded. Use `/compact` during
> long sessions to reclaim context space.
