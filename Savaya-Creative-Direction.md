# SAVAYA — Redesign Creative Direction

*Repositioning toward minimal private capital, editorial confidence, institutional calm, and family office discretion.*

---

## 1. Brand Direction Summary

Savaya should feel like a private institution that has nothing to prove and nothing to sell. The new direction trades warm regional luxury for cool, achromatic permanence — deep obsidian and graphite grounds, bone-white editorial type, and a single restrained natural accent instead of gold. The verbal voice becomes quieter and more declarative: short, certain statements about patience, conviction, governance, and permanence, with the promotional register stripped out entirely. Where the current site *explains*, the new Savaya *states* — and lets negative space, typographic authority, and discretion carry the credibility. The feeling to protect at every decision: a serious, global, generational steward of capital that speaks softly because it does not need to raise its voice.

---

## 2. Design Diagnosis — What Weakens the Current Site

**It codes regional, not global.** Beige and warm stone tones, plus repeated Abu Dhabi skyline framing, read as "Gulf luxury / hospitality." That narrows perceived reach and invites the wrong mental category — real-estate brochure or concierge brand — rather than global private capital.

**It over-explains, which reads as over-selling.** Four-plus dense paragraphs per principle, a full allocation table with three layers of caveats, and repeated restatements of "perpetual / generational" undercut the very discretion the firm claims. Truly private capital says less. Volume of copy is inversely correlated with perceived exclusivity here.

**The hierarchy is flat and additive.** The homepage stacks six-plus near-equal sections (pillars, philosophy, purpose, allocation, framework, contact). Nothing dominates, so nothing lands. There's no single confident moment the eye rests on.

**The chrome feels templated.** Generic card grids, evenly padded blocks, and centered symmetry are the default "corporate" look — competent but anonymous. It doesn't feel hand-built for a family of this standing.

**Tone drifts luxurious rather than institutional.** Phrases like "living legacy" and lifestyle-adjacent warmth pull toward brand storytelling. Institutional trust comes from restraint, structure, and precision — not sentiment.

Net effect: the site communicates *aspiration to* seriousness rather than *possession of* it. The redesign closes that gap by subtracting.

---

## 3. New Design System Direction

**Color palette — achromatic, institutional, no gold.**
The 60-30-10 system:
- **60% — Obsidian / Graphite** `#0B0D0C`, `#111413`, `#141716`. Deep, faintly cool-green undertone; never pure black.
- **30% — Smoke & Stone** text `#9BA29C`, dim `#6C726D`; hairlines at `rgba(237,234,227,0.06–0.10)`. Bone text for primary copy `#EDEAE3` (warm off-white, never pure `#FFFFFF`).
- **10% — Muted Eucalyptus** `#7E8F82` (desaturated sage-green). Used only in eyebrows, active nav, one hero rule, and data fills. This is the deliberate replacement for gold: it signals permanence and calm without desert-luxury or corporate blue.

**Typography — editorial serif + humanist sans.**
- **Display:** *Zodiak* (Fontshare) — a contemporary editorial serif with quiet character. Used large for hero and section headlines, with italics for emphasis words ("*generations*," "*one family*").
- **Text / UI:** *Switzer* (Fontshare) — a neutral humanist grotesk for nav, labels, metadata, and body.
- **Rules:** oversized, tightly-tracked serif headlines (`clamp()` up to ~7rem); wide-tracked uppercase 11px eyebrows; body kept short and airy. The serif/sans contrast is the whole personality — resist adding a third face.

**Spacing — generous and asymmetric.**
Large section padding (~130px desktop), a 1240px max width with wide 40px gutters, and a broken editorial grid (hero at ~1.55 / 0.85 columns) rather than centered symmetry. Negative space is a feature, not leftover room. Every section separated by a single 1px hairline — no heavy dividers or boxes.

**Photography / imagery — abstract and architectural, never regional or lifestyle.**
Move away from Abu Dhabi skylines and people-in-suits stock. Prefer: deep-shadow abstract architecture, macro material textures (stone, patinated metal, still water), and near-monochrome, low-key exposure. All imagery graded dark and desaturated so it recedes behind type. Ideally very few images — one atmospheric moment is more powerful than a gallery.

**UI style — restrained chrome.**
Flat surfaces, 2px (near-square) radii, no glossy cards. Depth comes from hairlines and grain, not drop shadows. A fine film-grain overlay and subtle radial gradient mesh give the dark ground texture without decoration.

**Cards / sections — lists over boxes.**
Replace the card grid with hairline-separated editorial rows (index numeral · headline · one line of copy). Data is presented calmly: thin 2px bars and typographic ranges rather than charts or chunky tables.

**Buttons — quiet and precise.**
Two only: a solid bone primary (`#EDEAE3` on obsidian, hovering to eucalyptus) and a hairline ghost. Small type, wide tracking, a single arrow that nudges 4px on hover. No pills, no glow.

**Nav — minimal, self-effacing.**
Transparent over the hero; on scroll it fades to a blurred obsidian bar with a hairline base. Serif wordmark left, sparse links right, one "Enquire" outline button, understated EN · AR.

**Animation — one signature moment, otherwise stillness.**
The hero headline reveals line-by-line via a masked upward wipe on load; supporting copy and stat fade in behind it. Elsewhere: soft rise-on-scroll and a 1.4s data-bar fill. Hover states are crisp with `cubic-bezier(.16,1,.3,1)` easing. All large motion gated behind `prefers-reduced-motion`. Calm, not busy.

---

## 4. Homepage Strategy — Fewer, Stronger Sections

Six sections total (down from the current eight-plus), each doing one job.

**01 · Hero — Establish permanence in five seconds**
*Purpose:* one confident statement of identity; drive a qualified enquiry, not signups.
*Headline:* **Perpetual capital. One family.**
*Support:* "Long-horizon capital, held without an exit date — deployed with discipline to preserve, grow, and transmit wealth across generations."
*Design notes:* left-anchored oversized Zodiak headline; right column carries a single restrained stat (∞ / "No terminal date"). Masked line-reveal on load. No skyline.

**02 · Approach — The thesis in one breath**
*Purpose:* state the worldview without a wall of text.
*Headline:* **We steward capital across *generations*, not quarters — accepting patience where others cannot wait.**
*Support:* two short columns — one on permanent mandate / long duration, one on preservation-before-return and tangible bedrock.
*Design notes:* opens on a hairline; headline dominates; supporting copy deliberately sparse.

**03 · Principles — Four convictions, calmly listed**
*Purpose:* convey discipline and selectivity.
*Headline (eyebrow):* Principles I–IV.
*Copy:* Patience is the advantage · Conviction over breadth · Governed by principle · Built for permanence — each with one tight sentence.
*Design notes:* hairline-separated rows (numeral · serif headline · one line). Subtle left-shift on hover. No cards.

**04 · Strategic Allocation — Calm data, not a spreadsheet**
*Purpose:* signal rigor and structure without disclosure.
*Headline:* **A long-term posture, reviewed against the IPS.**
*Support:* indicative ranges with a single tolerance caveat (not three).
*Design notes:* thin 2px bars that fill on scroll; ranges set in serif. Slightly lighter graphite ground to separate it.

**05 · Structure — Proof of institution**
*Purpose:* establish jurisdiction and legitimacy in a glance.
*Headline (eyebrow):* Structure.
*Content:* Jurisdiction (ADGM) · Structure (SFO — RSC) · Established (2020) · Horizon (Perpetual).
*Design notes:* four hairline-bordered fields, facts in serif. Zero prose.

**06 · Enquiry — Discretion as the close**
*Purpose:* invite the right conversation, deter the wrong one.
*Headline:* **A conversation begins *with discretion.***
*Support:* "SAVAYA does not accept unsolicited proposals or public applications. All enquiries are directed through the family office and held in absolute confidence."
*Design notes:* centered, maximal negative space, one primary button. Then a minimal footer.

---

## 5. Copy Rewrite Direction

Tone: refined, institutional, quiet, intelligent, global, minimal. Rewritten homepage copy:

> **Hero**
> Perpetual capital. One family.
> Long-horizon capital, held without an exit date — deployed with discipline to preserve, grow, and transmit wealth across generations.

> **Approach**
> We steward capital across generations, not quarters — accepting patience where others cannot wait.
> A permanent mandate removes the pressure of redemption windows and quarterly cycles. We hold long duration where it is properly compensated, and concentrate only where we hold real conviction.
> Preservation of purchasing power comes before return. Tangible assets form the bedrock; every allocation answers to a written policy before capital moves.

> **Principles**
> I — Patience is the advantage. No exit date, no benchmark to answer to. We access return premiums that time-constrained capital leaves on the table.
> II — Conviction over breadth. Concentrated positions in structural shifts the market underprices — not diversification for its own sake.
> III — Governed by principle. A formal Investment Policy Statement defines objectives, risk, and allocation. Every decision is measured against it first.
> IV — Built for permanence. Succession, governance, and asset selection all reflect one orientation: capital that belongs to the next generation.

> **Allocation**
> A long-term posture, reviewed against the IPS.
> Indicative target ranges express the family's strategic position. Tactical deviation is permitted within defined tolerance.

> **Enquiry**
> A conversation begins with discretion.
> SAVAYA does not accept unsolicited proposals or public applications. All enquiries are directed through the family office and held in absolute confidence.

Principle: cut every sentence that restates a prior one. If a line could appear in a brochure for a hotel or a fund pitch, delete it.

---

## 6. Visual Rules

**Remove**
- The beige / warm-stone palette and any gold accent.
- Abu Dhabi skyline photography and people-in-suits stock imagery.
- The dense multi-paragraph principle and purpose blocks.
- Card-grid layouts and heavy dividers/boxes.
- Repeated restatements of "perpetual / generational / legacy."

**Simplify**
- Eight-plus sections down to six.
- The allocation table to calm bars + one caveat.
- Navigation to a minimal serif wordmark, sparse links, one outline CTA.
- Buttons to exactly two styles.

**Avoid**
- Pure `#FFFFFF` / `#000000` blocks; corporate blue; VC-startup gradients; luxury-lifestyle warmth; centered symmetry as a default.
- Sentimental language ("living legacy") and any promotional register.

**Emphasize**
- Negative space and one dominant hero moment.
- Editorial serif authority with a single sans for structure.
- Hairlines, grain, and restraint over shadows and decoration.
- Discretion as the brand's loudest signal.

---

## 7. Creative Direction Keywords

**Ten keywords:** Perpetual · Discreet · Obsidian · Editorial · Restraint · Institutional · Achromatic · Sovereign · Tectonic · Quiet.

**Five style archetypes (conceptual territory, not to copy):**
1. **Editorial finance journals** (FT Weekend / Monocle) — serif authority, calm data, generous margins.
2. **Old-guard private capital** (ICONIQ, BDT & MSD, Cascade) — say little, prove much, no logos-on-parade.
3. **Swiss / institutional minimalism** (a private bank's discreet register, not its retail site) — grid discipline and precision.
4. **Architectural monographs** (El Croquis / a Tadao Ando volume) — deep shadow, material texture, stillness.
5. **Contemporary premium dark UI** (Vercel / Linear restraint, stripped of tech-startup color) — textured dark ground, hairline chrome, one accent.

---

*Companion deliverable: `savaya-redesign.html` — a working single-page prototype of this direction, viewable in any browser.*
