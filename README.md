# IEEE ITSC 2026 Workshop — Compiler Safety and Verification for ITS

Companion site for the half-day workshop at IEEE ITSC 2026 (Naples, 2026-09-15).

- Title: *Compiler Safety and Verification for Intelligent Transportation Systems: From C/C++ to Rust*
- Live URL after soft-launch: https://compiler-safety-its.github.io/itsc-2026-workshop/
- Source: single-page `index.html` + `style.css`. No build step.
- License: MIT for text/code; CC-BY for speaker-supplied media (see LICENSE).
- Contact: kangwon.lee@ieee.org

## Editing

Org members with `write` permission can edit `index.html` directly through the GitHub web editor. KL is the source of truth for substantive content edits (site is live since 2026-05-19; edits now land directly on the published page).

## Status (updated 2026-07-31)

- **[2026-08-11 update — SITE COMPLETE, BANNER REMOVED:** **All three speaker cards are final and live**, each carrying abstract + bio + headshot + org logo. Dániel Szűcs's talk materials arrived **2026-07-31** (229-word abstract, 106-word bio, headshot; title unchanged); **he reviewed the published card and confirmed "everything looks correct"**, then supplied HighTec's transparent SVG logo himself on **2026-08-10** (`../pub-root/pub-plan/26-09-ITSC-Workshop/26-08-10-1705-HighTec-Logo.txt`) — closing the last parity gap. **The under-construction banner has been REMOVED** (`6e28da8`): the lift condition below (bios/abstracts/headshots/logos final) is satisfied. The site is announcement-ready and the LinkedIn window **2026-08-11–18 opens today**. Nothing is outstanding from any speaker until the closing-panel feedback round (reply target 2026-08-24).
  - Asset notes: `assets/daniel-szucs.jpg` — the file Dániel sent was named `.png` but is JPEG data, renamed on copy. `assets/hightec-logo.svg` — Inkscape-authored, transparent; renders 110×36 at `max-height:36px`, alongside Solid Sands (57×36) and 2getthere (153×36).
  - ⚠ **Verifying a push:** GitHub Pages' CDN serves stale HTML for a minute or two after a push, and a `?v=` query string does **not** reliably bust it. Confirm a deploy against `raw.githubusercontent.com/.../main/index.html`, or `curl -H 'Cache-Control: no-cache'` the live URL — not by eyeballing the page immediately.]
- **[2026-07-19 update:** Co-organizer **Ayesha Choudhary** (IEEE ITSS Board of Governors, JNU) added to the Organizers section; footer corrected to "organized independently by Kangwon Lee, coordinated with the ITSC 2026 organizing committee" (pushed `2852d64`, verified live). HighTec presenter changed **Mario Cupelli -> Dániel Szűcs** (Mario cannot travel in September); Szűcs's title/abstract/bio/headshot are pending, so his speaker card and the under-construction banner stay up until they land. KW registered for ITSC 2026. Running status + scored TODO: `../pub-root/pub-plan/26-09-ITSC-Workshop/TODO.md`.]
- **[2026-06-29 update:** partner check-in email **SENT 2026-06-29** asking all three (Solid Sands / HighTec / 2getthere) to review the live site; **partner updates due 2026-07-14**. **Mario/HighTec abstract+bio still pending** on the live page (banner stays up until those land). Acceptance of the DEF CON CHV talk was shared with partners as encouragement in the same email. Evidence: `../pub-root/pub-plan/26-09-ITSC-Workshop/26-06-29-1532-email-partners-checkin.txt` (committed `ed9325c`).]
- **2026-06-09 sweep:** ITSC 2026 (Naples, Sep 15–18) confirmed; KL's LightPath LBR
  poster **ACCEPTED** (separate from this workshop — see
  `../pub-root/pub-plan/26-09-Light-Path/`). Workshop site state below is unchanged
  since 2026-06-06; under-construction banner still up pending partner deliverables.

### Earlier status (2026-06-06)

- Repository created 2026-05-06; **publicly launched 2026-05-19** (commit `4344fdf`).
- GitHub Pages is **LIVE** at the URL above (verified loading 2026-06-06), currently showing an
  intentional **partner-preview "under construction" banner** (restored in `674909b`) while speaker
  materials are assembled — schedule, speaker bios, and panel framework are already populated.
- Remaining: lift the under-construction banner once partner deliverables (bios/abstracts/headshots/
  logos) are final. Yang Xiao (2getthere) display-name preference already honored (`e9abb67`).
- Scratch: `del_this_reg.txt` (ITSC registration-portal capture) contains personal portal info — now gitignored; do not commit or publish.

## Conventions

- Lean academic register; thesis tagline appears once.
- No tracking, no analytics, no embedded fonts (system serif stack only).
- Korean characters are accepted in content, but the page itself ships in English.
