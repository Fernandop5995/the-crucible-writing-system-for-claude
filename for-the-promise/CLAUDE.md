# Crucible Project Memory

Book Title: For the Promise

## Project Info
- **Title**: For the Promise
- **Series**: [Series name TBD] Book 2
- **Genre**: Epic Fantasy
- **Target**: TBD words (epic fantasy typical: 120,000-180,000)
- **Current**: Chapters 1-4 written, Chapter 5 first half written (word count TBD — manuscript not yet added to draft/chapters/)

## Current Status
- **Phase**: writing (mid-draft; planning documents generated retroactively from author's roadmap)
- **Chapter**: 5 (second half "The Council" to draft next, then Chapter 6)
- **Story date**: 8th of Ashenfall, 982 A.M. — Late Summer, Month of Death (The Stranger)
- **Last Activity**: 2026-07-12

## Provenance Rules (IMPORTANT)
Planning documents were generated retroactively from the author's Book 2 roadmap
(`planning/source-roadmap.md` — the source of truth). Markers used throughout:
- Plain text = canon, taken from the author's roadmap
- **[PROPOSED]** = structural suggestion by the assistant; requires author approval before use in prose
- **[TBD]** = unknown; requires author input
Never treat [PROPOSED] or [TBD] content as canon when drafting.

## Project Rules
- Never invent characters not in the Constellation Bible
- Never create plot points not in the outline
- Always verify against story bible before writing
- Flag `[INVENTED: description]` for any invented details
- Save state after every scene
- Do NOT draft prose until the author's written chapters (1-5a) are added to
  `draft/chapters/` and a style profile is captured from them

## Commands
- `/crucible-suite:crucible-status` - Check progress
- `/crucible-suite:crucible-continue` - Resume from any phase
- `/crucible-suite:crucible-plan` - Start or continue planning
- `/crucible-suite:crucible-outline` - Generate chapter outlines
- `/crucible-suite:crucible-write` - Draft prose
- `/crucible-suite:crucible-edit` - Revise manuscript
- `/crucible-suite:crucible-review` - Trigger manual review
- `/crucible-suite:crucible-restore` - Restore from backup

## Recent Decisions
- Project set up retroactively from author's Book 2 roadmap (chapters 1-6 mapped; 1-4 + 5a written)
- POV rotation for chapters 1-6: Brunor → Elaine → Phoebe → Brunor → Elaine → Frederick
- Chapter 5 second half ("The Council") fully beat-mapped by author (6 beats)
- Chapter 6 ("The Golden Scale and the Hunt") mapped by author (two threads + convergence)

## Open Questions (author input needed)
- Upload written chapters 1-4 and 5 (first half) into `draft/chapters/` for style capture and continuity verification
- Provide Book 1 title/summary (referenced canon: Melody's intelligence on the Throng, the Wyrshade delivery, Alessa's ambush?)
- Target length and total chapter count for Book 2
- The "golden blade" Elaine wields in the Chapter 4 duel: her own weapon, or associated with Damien? (roadmap is ambiguous)
- Who are Uthred, West, and Mikah? (named in roadmap without context)
- Confirm/adjust all [PROPOSED] structure items: Book 2 forging question, Forge Point placements, which of the three pressures recedes during the Scattering movement
- Dark Mirror selection: Caelus is Elaine's stated Scaleblade foil — is he the book's Dark Mirror, or is it Tauvor/the Order?

---

> **How Context Works**: This root CLAUDE.md loads at session start.
> Subdirectory CLAUDE.md files (in `planning/`, `outline/`, `draft/`) load
> lazily when Claude reads files in those directories. The story bible and
> style profile are queried on-demand, not auto-loaded. Use `/compact` during
> long sessions to reclaim context space.
