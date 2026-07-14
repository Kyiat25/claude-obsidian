---
type: meta
title: "Operation Log"
updated: 2026-04-08
tags:
  - meta
  - log
status: evergreen
related:
  - "[[index]]"
  - "[[hot]]"
  - "[[overview]]"
  - "[[sources/_index]]"
---

# Operation Log

Navigation: [[index]] | [[hot]] | [[overview]]

Append-only. New entries go at the TOP. Never edit past entries.

Entry format: `## [YYYY-MM-DD] operation | Title`

Parse recent entries: `grep "^## \[" wiki/log.md | head -10`

---

## [2026-07-14] ruling | Exploit Weakness / Exploit Vulnerability naming collision resolved — Investigator keeps both, Rogue keeps neither
- Trigger: third HIGH-severity item from the class-system audit's contradiction ledger. [[Welcome to FEARS]] gave Investigator the ability "Exploit Weakness"; [[Class_breakdown]] later renamed Investigator's to "Exploit Vulnerability" and gave "Exploit Weakness" to [[Rogue]] instead — but [[Rogue]]'s own per-class deep-dive never actually uses that name (folded into Sneak Attack), while [[Investigator]]'s own deep-dive uses **both** names for a real two-stage feature chain (Exploit Vulnerability at 2nd level marks a studied target, Exploit Weakness at 5th level cashes it in for bonus damage). User's proposed split: Rogue = vulnerability (always looking for the flaw), Investigator = weakness (found through studying).
- **Resolved**: rather than hand Rogue the literal name "Exploit Vulnerability" (which would just relocate the collision onto Investigator's own already-detailed 2nd-level feature), Investigator keeps sole ownership of both "Exploit Vulnerability" and "Exploit Weakness" as its studied, sequential fantasy — vulnerability identified through observation, then exploited as a confirmed weakness once analysis completes. "Exploit Weakness" is retired as a Rogue term entirely: Rogue's version of the same flaw-spotting fantasy is reactive and in-the-moment, already fully expressed by Sneak Attack's advantage/flanking trigger, with no separate named ability needed — consistent with what Rogue's own deep-dive already chose to do.
- **Pages updated**: [[Rogue]] (bullet removed, naming-collision section rewritten with the tempo distinction), [[Investigator]] (naming-collision section confirms sole ownership), [[Class_breakdown]] (contradiction section marked resolved), [[FEARS Class Roster]] (collision note resolved), [[FEARS MOC]] (three separate "still open"/"unresolved" mentions struck through and resolved).
- Note: this closes the third of four HIGH items from the class-system audit. Remaining open: Warden/Ranger's missing Last Stand DCs.

## [2026-07-14] ruling | Called Shot save DC adopted from the excluded draft — risk lives in the attack penalty, not this save
- Trigger: second HIGH-severity item from the class-system audit's contradiction ledger — no confirmed source ever stated a DC for the Called Shot saving throw, only which ability the target saves with. The only candidate, `8+PB+attacker's ability modifier`, comes from [[The Dynamic Combat System (Excluded Draft)]], explicitly marked non-canonical. User's framing: make sure a Called Shot still feels like a real risk before ruling on the number.
- **Investigation**: checked [[Dynamic Combat System (DCS)]] and [[Damage Reduction]] — both already name "Risk and Reward" as an explicit design pillar and confirm the actual risk mechanism is the attack-roll penalty (−2 to −7 by location), traded against bypassing DR, tuned to be "worth it" once Total DR ≥ 10. That trade is already fully realized and confirmed across three independent sources, entirely independent of the missing save DC.
- **Resolved**: the missing save DC only governs whether a Called Shot's *bonus rider effect* (stun, disarm, prone, etc.) also lands on top of an already-risky hit — not the risk itself. Since adopting it doesn't disturb the confirmed risk/reward balance, `8+PB+attacker's ability modifier` is promoted to confirmed canon, matching the house `8+PB+ability` DC shape used everywhere else in FEARS. A narrow, source-specific promotion — the rest of the Excluded Draft (Momentum range, class-specific rules) remains design-history only.
- **Pages updated**: [[Called Shot]] (gap section replaced with the resolved formula + reasoning, excluded draft added to `sources`), [[The Dynamic Combat System (Excluded Draft)]] (Called Shot DC bullet marked adopted), [[FEARS MOC]] (open-question line struck through and resolved).
- Note: this closes the second of four HIGH items from the class-system audit. Remaining open: the Rogue/Investigator "Exploit Weakness"/"Exploit Vulnerability" naming collision, and Warden/Ranger's missing Last Stand DCs.

## [2026-07-14] ruling | Fracture Save DC "conflict" resolved — two distinct mechanics, not one disputed formula
- Trigger: surfaced in a full 24-class + shared-chassis audit as the top HIGH-severity contradiction — [[Spell Critical]] gives the Fracture Save DC as `10 + PB`, while [[Sanity & Focus in Combat]] and [[Fracture Whispers]] both independently give `13 + Whisper Points`, all three confirmed canon. User's ruling: "They are two different things one is when seeing a spell critical and the other is the use of whisper points."
- **Resolved**: "Fracture Save" names two mechanics sharing a label — the **Whisper Fracture Save** (general-purpose, DC `13 + Whisper Points`, self-driven by a character's own accumulated Whisper Points, per [[Sanity & Focus in Combat]]/[[Fracture Whispers]]) and the **Spell Critical Fracture Save** (narrow, DC `10 + PB`, triggered when a creature already Frightened by a caster's Spell Critical fails its follow-up save, scaled to the caster's own PB). Not a contradiction requiring a pick-one ruling.
- **Pages updated**: [[Fracture Save]] (restructured into the two named variants, `contradiction` tag removed, `[!contradiction]` callout replaced with `[!resolved]`), [[Spell Critical]], [[Sanity & Focus in Combat]], [[Fracture Whispers]] (each cross-reference updated to point at the resolution instead of the open conflict).
- Note: this closes the highest-severity item on the class-system audit's contradiction ledger; the other three HIGH items from that audit (Called Shot's missing DC formula, the Rogue/Investigator "Exploit Weakness"/"Exploit Vulnerability" naming collision, and Warden/Ranger's missing Last Stand DCs) remain open.

## [2026-07-13] ingest | Final cosmology/Eldritch wave — 12 sources, 68 pages
- Sources: `.raw/Guide to the Eldritch_Forces.md`, `.raw/The Hollow Thread.md`, `.raw/The Lie of Godhood.md`, `.raw/Three Pillars of Magical Flow.md`, `.raw/Weave and Magic.md`, `.raw/Weave of Creation.md`, `.raw/Luminous Echo.md`, `.raw/Umbral Veil.md`, `.raw/Veiled Star.md`, `.raw/Creations Misunderstanding.md`, `.raw/World Anchors and the Loom-City System.md`, `.raw/Eldritch Zones and Manifestations.md`
- Summary: closes out the entire remaining `.raw/` cosmology backlog in a single pass, at the user's explicit request to ingest all non-ingested files. The largest single ingest this vault has performed by page count.
- Pages created (68): [[Guide to the Eldritch Forces]]; 9 Eldritch Gods ([[Nhal'Zereth]], [[Ith'Quess]], [[Vael'Akir]], [[Xey'Tazun]], [[Ul'Naresh]], [[Zhurr'Kael]], [[Esh'Tarah]], [[Mirag'Nael]], [[Vezherak]]); [[Eldritch Moons]] hub + 14 Moons ([[Howling Moon]], [[Shattered Moon]], [[Scorching Moon]], [[Vacuous Moon]], [[Glowering Moon]], [[Glacial Moon]], [[Slumbering Moon]], [[Yellow Crown]], [[Creeping Tarlight]], [[Krakenlight]], [[Sanguine Eclipse]], [[Blood Moon of Rebirth]], [[Weeping Waxing]], [[False Dawn]]); [[Eldritch Spirits]] hub + 15 Spirits ([[The Faceless Choir]], [[The Writhe-Twin]], [[The Echo of the Empty Name]], [[Vathryn, the Hollowed Child]], [[The Shuddering Cradle]], [[Mother-Shell Elessh]], [[Eshari's Mirror]], [[The Pane-Creep]], [[Velai, the Remembered Stranger]], [[Ulzen, the Sleepless Host]], [[The Quilt-Worm]], [[Marrowbell]], [[The Ink-Root]], [[The Glyph Maw]], [[The Bonechain]]); [[The Null Reflection]]; [[The Hollow Thread]]; [[Vel'Zyren]]; [[Veiled Star]]; [[Primal Glyphs]], [[Universal Glyphs]], [[Elemental Glyphs]], [[Form Glyphs]], [[Personal Glyphs]], [[Glyph of Severance]]; [[Luminous Echo]], [[Umbral Veil]]; [[Leylines]], [[Wells of Power]], [[Astral Conduits]], [[Three Pillars of Magical Flow]]; [[Weave and Magic]], [[Weave of Creation]]; [[Creations Misunderstanding]]; [[Earth Pantheon]], [[Spirit Pantheon]], [[Fire Pantheon]], [[Water Pantheon]], [[Air Pantheon]]; [[The Lie of Godhood]]; [[World Anchors and the Loom-City System]]; [[Eldritch Zones and Manifestations]]
- Pages updated: [[Divine Sparks]] (Mythalix/Spark-origin taxonomy added), [[Astralor]] (new contradiction flagged), [[Ashkarra]] (Day of Twelve Shadows detail added), [[The Threadbearer Crisis]] (survivor contradiction flagged), [[The Weave]] (Creations Misunderstanding convergence noted, gap-closed), [[FEARS MOC]], [[index]], [[hot]]
- Key findings:
  - **Three new contradictions.** (1) [[The Lie of Godhood]] reframes [[Astralor]] as "not a god, but the Law of Becoming" — a pattern, not a person — conflicting with every other source's personified Astralor and his sibling bond with [[Aeloria]]. (2) [[World Anchors and the Loom-City System]] names [[Aeravae]], not Kel Varyan, as the sole surviving Threadbearer in [[The Threadbearer Crisis]]. (3) [[Eldritch Zones and Manifestations]] introduces a parallel Sanity Corruption Score not merged with the vault's existing Corruption track.
  - **One contradiction narrowed further.** [[Creations Misunderstanding]] independently confirms Aeloria's ignorance of [[The Restorer]], making it 3-of-5 sources agreeing against [[Hidden Cosmology Thread System]]'s lone dissent — still documented as unresolved, not settled by count.
  - **A new adjacent domain opened and closed in the same pass**: the Eldritch material (Gods/Spirits/Moons/Null Reflection) was previously unknown to this vault; it's now fully documented at full per-entity granularity, per explicit user direction after a scope-calibration question.
  - **The Day of Twelve Shadows** is now explicitly named and cross-referenced: all twelve Eldritch Moons aligning during [[Ashkarra]]'s fall, tying the Thread-mechanical catastrophe directly to the Eldritch Moon material for the first time.
- Note: 68 new addresses allocated (c-000186 through c-000253); counter advanced from 186 to 254. **The uningested cosmology cluster that began at 15 files is now fully closed — 0 files remain in `.raw/`.**

## [2026-07-13] ingest | Creation World
- Source: `.raw/Creation World.md`
- Summary: fifth cosmology source, likely the narrative root [[How the Five Layers Shape the Creation World]] partially systematizes — same four Primal Forces, same forge/loom framing, same "none of them realize they're not alone" capstone, but no Layer/Glyph taxonomy of its own
- Pages created: [[Creation World]], [[Divine Sparks]]
- Pages updated: [[The Weave]] (corroboration note added to the three-way contradiction), [[Astralor]], [[Aeloria]] (corroboration note + Divine Sparks section), [[The Whispering Dark]], [[The Restorer]] (both given Divine Sparks sections), [[How the Five Layers Shape the Creation World]] (relationship note + gap list updated), [[index]], [[hot]], [[FEARS MOC]]
- Key insight: independently corroborates [[Twins of Creation]]'s specific claim over [[Hidden Cosmology Thread System]]'s — Aeloria does not know [[The Restorer]] exists, and only ever questions, never resolves, what she witnesses when erased things reappear. Now 2-of-4 sources agreeing on this specific point, still documented as unresolved rather than treated as a tiebreaker, consistent with this cluster's standing convention of preserving disagreement rather than voting on it. Introduces **Divine Sparks** — a wholly new concept, absent from every other cosmology source ingested so far: unintended crystallizations of potential divinity, born from the collision of all four Primal Forces' actions at once, that became the origin point of the first gods.
- Note: two new addresses allocated (c-000184, c-000185); counter advanced from 184 to 186. **Uningested cosmology cluster narrowed from 10 to 9 files.**

## [2026-07-12] ingest | World Anchors and Thread System
- Source: `.raw/World Anchors and Thread System.md`
- Summary: fourth cosmology source, written in a mortal/scholarly register rather than the mythic DM-secret register of the prior three — almost certainly the exact "World Anchors document" [[Hidden Cosmology Thread System]] cited as its own Tier One baseline. Introduces five named Loom-Cities, elevates the Ashkarra Catastrophe into the setting's central historical trauma, gives Aeravae's cooperative founding its own page, massively expands Threadbearer mechanics, and surfaces a live campaign hook
- Pages created: [[World Anchors and Thread System]], [[Loom-Cities]], [[Ashkarra]], [[Aeravae]], [[The Threadbearer Crisis]]
- Pages updated: [[World Trees]] (new `[!contradiction]` — Vatharun named as creator), [[Threadbearers]] (mortal mechanics section added: the Beaming, death/succession, cultural variance), [[Loom-Wardens]] (cross-referenced into the crisis), [[index]], [[hot]], [[FEARS MOC]]
- Key insight: **New, major contradiction against [[World Trees]].** [[Hidden Cosmology Thread System]] explicitly states World Trees' origin should stay unknown "even to the DM" — five competing theories, no canonical answer, framed as a permanent design choice. This source instead states flatly, with no hedge or competing theory offered, that World Trees were "planted by Vatharun (Earth Pantheon deity)." Flagged with `[!contradiction]`, not resolved — same treatment as the standing three-way Aeloria/Restorer/Whispering-Dark knowledge contradiction on [[The Weave]]. Also establishes a live, ongoing campaign situation (not historical background): four of five Threadbearers assassinated by the Drow, four World Anchors dimmed, a three-way race underway over each new Threadbearer manifestation — captured on [[The Threadbearer Crisis]].
- Note: five new addresses allocated (c-000179 through c-000183); counter advanced from 179 to 184. **Uningested cosmology cluster narrowed from 11 to 10 files.**

## [2026-07-12] ingest | Twins of Creation
- Source: `.raw/Twins of Creation.md`
- Summary: third cosmology source, and the first to directly contradict rather than extend what came before. Confirms [[Astralor]] and [[Aeloria]] are literal siblings, "the Twins of Creation," and gives both real personalities for the first time
- Pages created: [[Twins of Creation]]
- Pages updated: [[The Weave]] (three-way comparison table added), [[Dór-o Estel]], [[Astralor]], [[Aeloria]] (both substantially rewritten), [[The Whispering Dark]], [[The Restorer]] (Restorer elevated, Whispering Dark's awareness revised), [[Hidden Cosmology Thread System]] (backlinked, contradiction noted from the other direction), [[index]], [[hot]], [[FEARS MOC]]
- Key insight: **Directly contradicts [[Hidden Cosmology Thread System]]'s central claim.** That source said Aeloria "ONLY SHE KNOWS EVERYTHING," including the Restorer's existence. This source says the opposite: Aeloria does not know the Restorer exists, misunderstands the Whispering Dark's true nature, and believes she and her brother are the only two forces shaping reality. It instead elevates the Restorer to "the only force that sees the entire pattern," with the Whispering Dark given a strange aware-but-silenced middle position — "knows the Restorer exists, but cannot explain this to anyone." Combined with the first source's "no one knows" framing, this produces **three internally-coherent, mutually-incompatible answers** to the single question "who understands this cosmology" — none of which share an obvious provenance tie-breaker (two sources marked `complete`, one `canonical`, and the new contradiction isn't with the `canonical` one). Documented as a comparison table rather than silently resolved, and deliberately treated as unreliable in-universe myth-telling — different tellings from different vantage points — rather than a continuity error needing a fix.
- Note: new address c-000178 allocated; counter advanced from 178 to 179. **Uningested cosmology cluster narrowed from 12 to 11 files.**

## [2026-07-12] ingest | Hidden Cosmology Thread System
- Source: `.raw/Hidden Cosmology Thread System.md`
- Summary: second cosmology ingest, directly building on and substantially reframing [[How the Five Layers Shape the Creation World]]. Marked `canonical` in its own frontmatter — stronger provenance than the first source's `complete`
- Pages created: [[Hidden Cosmology Thread System]], [[Loom-Wardens]], [[Threadbearers]], [[World Trees]]
- Pages updated: [[The Weave]] (second contradiction layered onto the first), [[Dór-o Estel]] (cluster now sizeable enough to flag for a future hub page), [[Astralor]], [[Aeloria]] (both substantially rewritten with major new characterization), [[The Whispering Dark]], [[The Restorer]] (both given a concrete Thread-rotation role and the Ashkarra Catastrophe case study), [[Pattern Keeper]], [[Thread Merchant]] ([[FEARS Advanced Backgrounds]] Batch 3 — both flagged as sitting closer to this hidden cosmology than previously apparent), [[index]], [[hot]], [[FEARS MOC]]
- Key insight: **Astralor and Aeloria are named "the Twins of Creation."** Most significant single finding: [[Aeloria]] alone is revealed to secretly know almost everything — deliberately concealing this even from [[Astralor]] — which sits in real, unresolved tension with the first source's "none of them know" Final Truth (flagged on [[The Weave]] and [[Aeloria]]'s own pages, not silently reconciled). Thread rotation, previously an unexplained in-world mystery, is now mechanically explained as three uncoordinated cosmic forces (Aeloria/Whispering Dark/Restorer), illustrated with a named historical catastrophe (the Ashkarra Catastrophe — three consecutive Spirit Thread alignments desynchronizing all three forces at once). [[Threadbearers]] and the [[Loom-Wardens]] are both new, richly-detailed concepts — the Wardens in particular are a secret organization that has been unknowingly serving Aeloria the entire time they believed they served something else. [[World Trees]] is notable as the first concept in this cluster explicitly meant to stay unexplained by design, not by ingest order.
- Note: new addresses c-000174 through c-000177 allocated; counter advanced from 174 to 178. **Uningested cosmology cluster narrowed from 15 to 12 files** — `Twins of Creation.md` in particular is now a clear next-priority target given this source's direct naming of that title.

## [2026-07-12] ingest | How the Five Layers Shape the Creation World
- Source: `.raw/How the Five Layers Shape the Creation World.md`
- Summary: first ingest of a new DM-only cosmology domain, entirely separate from the class/background mechanics work this session has otherwise covered. Structures [[The Weave]] — previously a thin stub built only from oblique mentions — as a five-Layer "Creation World" proving-ground cosmology
- Pages created: [[How the Five Layers Shape the Creation World]], [[Astralor]], [[Aeloria]], [[The Whispering Dark]], [[The Restorer]] (the four Primal Forces embodying the first Layer)
- Pages updated: [[The Weave]] (elaborated from a stub into a structured page, new contradiction flagged), [[Dór-o Estel]] (new section distinguishing setting-level cosmology from FEARS-ruleset mechanics), [[Wizard]], [[Sorcerer]], [[Sangromancer]], [[Narrative Identity]], [[Four Threads of the Mind]] (cross-referenced), [[FEARS MOC]], [[index]], [[hot]]
- Key insight: **Genuine tension, flagged not resolved** — this source states the four Primal Forces are blind and unwatching ("do not know the Creation World exists"), while [[Four Threads of the Mind]] personifies the Weave as an attentive, marking presence ("The Weave watches. The Weave waits"). Not reconciled. **User-prompted structural clarification**: the user asked whether this content should get its own MOC, and separately whether it's portable to non-FEARS systems — checking [[Dór-o Estel]]'s existing page confirmed this is setting-level lore (would remain true under any ruleset), not FEARS-mechanics content, so [[Dór-o Estel]]'s page was updated to make that distinction explicit rather than leaving it implicitly bundled into FEARS. Decided against a new MOC for now — filed under FEARS MOC, the vault's only domain-level MOC, with a note that a dedicated hub page (not a full MOC) would make sense if the wider cluster below gets ingested. **Major gap surfaced**: checking `.raw/` while ingesting this file revealed 15 more uningested cosmology sources — 5 directly adjacent (`Creation World.md`, `Creations Misunderstanding.md`, `Twins of Creation.md`, `Weave and Magic.md`, `Weave of Creation.md`) and 10 more in a broader Eldritch/Thread/Loom-City cluster (`Eldritch Zones and Manifestations.md`, `Guide to the Eldritch_Forces.md`, `Luminous Echo.md`, `The Hollow Thread.md`, `The Lie of Godhood.md`, `Three Pillars of Magical Flow.md`, `Umbral Veil.md`, `Veiled Star.md`, `World Anchors and Thread System.md`, `World Anchors and the Loom-City System.md`) — none of which were previously known to this vault's bookkeeping. Only the one requested file was ingested; the rest is a substantial follow-up, not attempted here.
- Note: new addresses c-000169 through c-000173 allocated; counter advanced from 169 to 174.

## [2026-07-12] lint | Post FEARS Advanced Backgrounds lint pass
- Source: none — health check, not an ingest
- Summary: re-ran the wiki-lint scripts against the vault after the 3-batch Advanced Backgrounds ingest (214 pages, up from 151). Result: clean — 0 genuine bugs introduced by the ingest. Address validation clean (164 addressed pages, 0 collisions). Frontmatter gaps: 0. Empty sections: 0 across all of `wiki/notes/`. The only new dead links were 3 intentional forward-references ([[Sailor]], [[Urchin]], [[Outlander]]) documenting a known, deliberate gap — not bugs.
- Pages created: `wiki/meta/lint-report-2026-07-12-post-backgrounds.md`
- Pages updated: none
- Key insight: the discipline established during the original 24-class lint cleanup (plain-text `sources:` paths, complete frontmatter, address allocation via the counter) held up perfectly across 3 large, separately-ingested batches with zero drift.
- Note: this pass is what surfaced the Sailor/Urchin/Outlander gap as worth closing, leading directly to the homebrew entry below.

## [2026-07-12] homebrew | Sailor, Urchin, Outlander (closing the Advanced Backgrounds gap)
- Source: none — original content, no `.raw/` file exists for any of these three
- Summary: wrote the three PHB backgrounds ([[Sailor]], [[Urchin]], [[Outlander]]) that Batch 1 flagged as "adaptable but not yet written" and neither Batch 2 nor Batch 3 ever delivered, despite Batch 3 explicitly billing itself as covering "remaining gaps." The FEARS Advanced Backgrounds system is now 64 entries, not 61.
- Pages created: [[Sailor]], [[Urchin]], [[Outlander]]
- Pages updated: [[FEARS Advanced Backgrounds]] (new homebrew section + table, updated total count, updated frontmatter), [[FEARS MOC]], [[index]], [[hot]], [[Ship Captain]] and [[Fisher]] (backlinks to Sailor), [[Criminal]] (backlink to Urchin), [[Scout]] (backlink to Outlander)
- Key insight: first pass closely templated each new background on its nearest existing cousin, but the user asked for genuine mechanical distinction rather than a reskin — redone so each uses an axis its cousin doesn't. [[Sailor]]: debts owed by disaster survivors + a superstitious reputation, no income table (vs. [[Ship Captain]]'s ownership/command track and [[Fisher]]'s trade income). [[Urchin]]: weaponized social invisibility — structurally never registering as a threat or suspect to the powerful (vs. [[Criminal]]'s hierarchy-and-profit enterprise). [[Outlander]]: belonging over expertise, sought out rather than hired — the only background in the full 64-entry system with no income figure at any rank (vs. [[Scout]]'s paid wilderness-guide career).
- Note: new addresses c-000166 through c-000168 allocated; counter advanced from 166 to 169. No manifest `sources` entry created (no `.raw/` file involved) — only `address_map` entries added.

## [2026-07-12] ingest | FEARS Advanced Backgrounds - Batch 3 (FINAL)
- Source: `.raw/FEARS Advanced Backgrounds - Batch 3.md`
- Summary: third and final batch of the FEARS Advanced Backgrounds progression system — 26 backgrounds across 8 source-defined categories, completing the system at 61 total backgrounds across 3 batches
- Pages created: [[Apprentice Spellcaster]], [[Alchemist]], [[Rune Carver]], [[Diviner]], [[Thread Merchant]] (Magic-Focused); [[Druidic Initiate]], [[Beastmaster]], [[Forester]], [[Herbalist]] (Druidic/Nature); [[Architect]], [[Scribe]], [[Lamplighter]] (Urban Specialist); [[Herald]], [[Minstrel]] (Social/Performance); [[Fence]], [[Forger]], [[Poisoner]] (Criminal Specialist); [[Miner]], [[Fisher]], [[Farmer]], [[Skinner]] (Working Class); [[Inquisitor]], [[Pilgrim]] (Specialized Religious); [[Pattern Keeper]], [[Fracture Scout]], [[Corruption Warden]] (FEARS-Specific) — 26 pages
- Pages updated: [[FEARS Advanced Backgrounds]] (Batch 3 table, updated progression-timing note, updated Corruption tie-in, updated setting-integration section, marked system complete), [[Corruption]] (tie-in note updated from "unimplemented" to "partially implemented," citing Inquisitor/Corruption Warden), [[Bard]] (flagged the Minstrel naming collision), [[index]], [[hot]], [[FEARS MOC]]
- Key insight: **Second genuine naming collision** — Batch 3 names a background "Minstrel / Bard," colliding with the existing Bard class exactly the way Batch 2's "Investigator" background collided with the Investigator class. Resolved identically (filed under the non-colliding half of the name). **Progression-timing contradiction resolved to 2-vs-1**: Batch 3's session counts match Batch 2's exactly, confirming Batch 1 as the outlier rather than an unresolvable coin-flip. **Corruption design intent now implemented**: Inquisitor and Corruption Warden give Batch 2's abstract "Corruption risk" language real numbers (save advantage, immunity, a once-per-year Corruption-reduction capstone) — the first concrete numeric Corruption interaction anywhere in this background system. Momentum and Breaking Point integration remain entirely unimplemented across all 3 batches despite being named in Batch 2's design intent. Batch 3's three FEARS-specific backgrounds (Pattern Keeper, Fracture Scout, Corruption Warden) are also the first content anywhere in this vault to give "Faith of the Bound Pattern," Threads, and Loom-Cities genuine mechanical substance rather than just naming them. **[[Sailor]], [[Urchin]], [[Outlander]] remain undeveloped** despite Batch 3 explicitly billing itself as covering "the remaining gaps" — now reads as a genuine, permanent omission rather than a temporary lag.
- Note: new addresses c-000140 through c-000165 allocated (26 pages); counter advanced from 140 to 166. **This closes the FEARS Advanced Backgrounds ingest arc — all 3 known batches are now in the vault.**

## [2026-07-12] ingest | FEARS Advanced Backgrounds - Batch 2
- Source: `.raw/FEARS Advanced Backgrounds - Batch 2.md`
- Summary: second of 3 batches in the FEARS Advanced Backgrounds progression system — 20 more backgrounds, extending the existing hub page rather than creating a new one
- Pages created: [[Scout]], [[Ship Captain]], [[Spy]], [[Archaeologist]], [[City Watch]], [[Diplomat]], [[Gladiator]], [[Hermit]], [[Investigator (Background)]], [[Knight]], [[Noble]], [[Pirate]], [[Smuggler]], [[Eldritch Scholar]], [[Exorcist]], [[Hedge Witch]], [[Monster Hunter]], [[Occultist]], [[Rat Catcher]], [[Vampire Hunter]] (20 pages)
- Pages updated: [[FEARS Advanced Backgrounds]] (added the 20-background table, setting-integration factions/places, Sanity/Focus/Corruption/Momentum tie-in notes, updated conversion notes and the "still not developed" list), [[Investigator]] (flagged the naming collision with the new background), [[Corruption]], [[Momentum]], [[Breaking Points]] (each got a note that Batch 2's system-level design intent isn't mechanically implemented per background), [[index]], [[hot]], [[FEARS MOC]]
- Key insight: **Genuine naming collision** — Batch 2's "Investigator" background is entirely unrelated to the [[Investigator]] class mechanically, but shares the name; resolved via filename disambiguation (`Investigator (Background).md`), flagged on both pages rather than silently avoided. **Genuine contradiction** — Batch 1 and Batch 2 give different session-count ranges for the same rank-transition timing (Batch 2 consistently slower at every tier); left unreconciled, noted as a GM judgment call. Batch 2 also introduces several concrete named Dór-o Estel factions/places (Veltharyn's Phoenix Knights, Elarion's Border Wardens, Talanthar's Griffon Riders, Loom-Cities, Kel Varyan, Faith of the Bound Pattern) — flagged inline on the hub page rather than given dedicated pages, since none has more than a name and one-line category.
- Note: new addresses c-000120 through c-000139 allocated (20 pages); counter advanced from 120 to 140. **One more batch (`Batch 3`) remains uningested in `.raw/`.**

## [2026-07-12] ingest | FEARS Advanced Backgrounds - Batch 1
- Source: `.raw/FEARS Advanced Backgrounds - Batch 1.md`
- Summary: first ingest of a new FEARS subsystem — a 4-rank progression track layered onto standard PHB/Grim Hollow backgrounds, replacing static background-as-flavor-text with an ongoing advancement system running alongside class levels
- Pages created: [[FEARS Advanced Backgrounds]] (hub — power budget, progression timing, downtime activities, DM integration notes, conversion notes, and the not-yet-developed backgrounds list), [[Soldier]], [[Criminal]], [[Acolyte]], [[Folk Hero]], [[Guild Artisan]], [[Sage]], [[Charlatan]], [[Entertainer]], [[Pit Fighter]], [[Pauper (Vagabond)]], [[Bounty Hunter]], [[Merchant]], [[Witch Hunter]], [[Plague Doctor]], [[Grave Keeper]] (16 pages total)
- Pages updated: [[index]], [[hot]], [[FEARS MOC]], [[Wanted Score]], [[Black Market]]
- Key insight: this is a genuinely new system, not a class deep-dive — no cross-cutting hub pages (Momentum, Damage Reduction, etc.) apply here, since backgrounds don't interact with combat mechanics. The natural cross-references are the existing social/reputation pages instead: [[Criminal]] and [[Bounty Hunter]] connect to [[Wanted Score]] and [[Black Market]]. One flagged tension, not resolved: [[Witch Hunter]]'s premise is antagonistic to the [[Witch]] class, and the source never addresses the obvious same-party conflict. Explicitly written for Dór-o Estel's setting, with several Tier 3/4 backgrounds tagged dark-fantasy/Grim Hollow-inspired.
- Note: new addresses c-000104 through c-000119 allocated (16 pages); counter advanced from 104 to 120. **Two more batches (`Batch 2`, `Batch 3`) remain uningested in `.raw/`** — this covers Batch 1's 15 backgrounds only.

## [2026-07-12] lint-fix | Technical lint items from the 2026-07-12 report cleaned up
- Source: `wiki/meta/lint-report-2026-07-12.md`, applied after the content-ruling pass above concluded
- Summary: fixed every "safe to auto-fix" item from the lint report — dead links and frontmatter gaps
- Pages updated: ~54 files with `sources:`/`related:` frontmatter had `"[[.raw/X.md]]"` stripped to plain-text `".raw/X.md"` (~100 instances); `wiki/concepts/Persistent Wiki Artifact.md`, `Query-Time Retrieval.md`, `Source-First Synthesis.md` (dropped the `?` from `How does the LLM Wiki pattern work?` links to match the real filename); `wiki/references/transport-fallback.md` and `methodology-modes.md` (converted `[[wiki-cli]]`/`[[wiki-mode]]` to plain-text skill paths, added missing `created`/`tags`); `wiki/mocs/FEARS MOC.md` (added `status`/`updated`); `wiki/meta/retrieval-benchmark-v1.7.md`, `2026-04-15-release-report-session.md`, `2026-04-15-slides-and-release-session.md`, `boundary-frontier-2026-04-24.md` (added missing `created`)
- Key insight: left three things deliberately untouched — the `log.md`/`hot.md` occurrences of the same `?`-filename mismatch (append-only historical entries), the `wiki/folds/` rollup file's `wiki-fold` references (frozen historical artifact), and `tiling-report-2026-04-24.md`'s missing frontmatter (auto-generated report, not hand-authored content, likely intentional).
- Note: no manifest entry — mechanical lint cleanup, not new content or a ruling.

## [2026-07-12] ruling | Class Reactions' last four pool-structure exceptions resolved
- Source: user ruling, given directly in conversation
- Summary: resolved the four remaining open items from [[Class Reactions]] — Monk (header/mechanics mismatch), Inventor (7th-level gate), Investigator (Predictive Step's separate budget), Wizard (Counterspell Instinct's separate budget)
- Pages updated: [[Class Reactions]], [[Monk]] (both `[!contradiction]`-style write-ups replaced — reactions corrected from Focus-only costs to shared PB pool uses, matching the header rather than the original per-reaction text), [[Inventor]] (7th-level gate ruled intentional slow-build design), [[Investigator]] (Predictive Step ruled explained by Bloodied Analysis's matching INT-mod-per-long-rest budget), [[Wizard]] (Counterspell Instinct noted as already self-explained by the source, no ruling needed), [[FEARS MOC]] (cluster-wide summary updated — all pool-structure questions now closed)
- Key insight: **Monk is the one genuine correction, and it went the opposite direction from the Damage Reduction precedent** — rather than the detailed mechanics overriding the summary header, the user ruled the header (shared PB pool) was correct and the individual reaction costs (Focus) were the error, aligning Monk with the universal default instead of carving out an exception. Investigator's resolution surfaced a real parallel (Bloodied Analysis already uses the same INT-mod-per-long-rest shape) that wasn't obvious from Class Reactions.md alone — needed a look at Investigator's full kit to find. Inventor's late gate was confirmed intentional given the class's "can't react without preparation" identity. Wizard's exception required no ruling at all — the source document already explains it via Magic Sense.
- Note: no manifest entry (no `.raw/` source involved). This closes every open question that came out of the "lint the wiki" → open-questions arc across this entire session — [[Last Stand]], [[Class Reactions]], [[Damage Reduction]], [[Weapon Mastery]], and [[Evasion]] now have zero unresolved `[!contradiction]` callouts from the 24-class FEARS pass.

## [2026-07-12] ruling | Deep-dive-wins policy applied to remaining DR/Weapon Mastery/Evasion conflicts
- Source: user ruling (established earlier in this session's Q&A pass), applied to the pages that were left pending
- Summary: wrote the previously-decided "per-class deep-dive is authoritative over the old DCS-era summary" ruling into the eight remaining open conflicts: five [[Damage Reduction]] contradictions (Barbarian, Monk, Paladin, Ranger, Shaman), two [[Weapon Mastery]] table conflicts (Tattooist, Shaman), and the [[Evasion]] Ranger conflict
- Pages updated: [[Damage Reduction]], [[Barbarian]], [[Monk]], [[Paladin]], [[Ranger]], [[Shaman]] (all `[!contradiction]` callouts downgraded to resolved `[!note]`s, old formulas struck through, deep-dive formula confirmed as current rule), [[Weapon Mastery]] (Tattooist and Shaman moved from the Half-Martials row to Non-Martials, matching their deep-dives), [[Evasion]] (Ranger's Favoured Enemy bonus resolved to advantage, no WIS scaling; removed the stale "zero drift" mention of the old formula), [[FEARS MOC]] (cluster-wide summary rewritten to reflect all resolutions)
- Key insight: **Paladin's case is the one true removal, not a formula swap** — the old "Aura = CHA mod DR to allies" claim doesn't survive at all; Aura of Protection is saves-only in the deep-dive, so the DR claim was deleted rather than replaced with a corrected number. Every other resolution simply swapped in the deep-dive's formula. With this pass, [[Damage Reduction]], [[Weapon Mastery]], and [[Evasion]] have no remaining open `[!contradiction]` callouts from the 24-class FEARS ingest — the only genuinely unresolved cross-class item left is [[Class Reactions]]' four remaining pool-bypass exceptions (Monk, Investigator, Wizard, Inventor), which weren't part of this ruling.
- Note: no manifest entry (no `.raw/` source involved) — this closes out the open-questions pass that began with "lint the wiki."
- Source: user ruling, given directly in conversation
- Summary: resolved the last open Damage Reduction item — Witch's "Hex of Frailty" (an old DCS-summary claim the deep-dive never detailed, since Coven-specific features were left generic) — by writing it as new content rather than leaving it permanently unconfirmed
- Pages updated: [[Witch]] (added Hex of Frailty as a 6th-level Coven Feature for Coven of the Hidden Moon), [[Damage Reduction]] (callout resolved, cross-linked), [[FEARS MOC]] (cluster-wide summary updated)
- Key insight: **Designed at 6th level, flat −2 DR, riding on the existing hexed/marked-target mechanic (Malefic Touch/Witches Mark) rather than adding a new action-economy cost.** Balance rationale: matches the cluster's other enemy-DR-reduction effects exactly ([[Ranger]]'s Hunter's Mark/Colossus Slayer, [[Inventor]]'s Overclock, all flat −2), and 6th level was already a generic "Coven Feature" slot in Witch's own table, so no structural change was needed to the level progression.
- Note: no manifest entry (no `.raw/` source involved) — new content designed to close a gap, following the same pattern as [[Sorcerer]]'s Last Stand closure.

## [2026-07-12] ruling | Cleric/Druid Class Reactions pool exceptions explained
- Source: user ruling, given directly in conversation
- Summary: resolved whether Cleric's Sacred Interposition and Druid's three reactions bypassing the shared PB pool were unexplained anomalies or consistent with the classes' own established resource design
- Pages updated: [[Class Reactions]] (both callouts downgraded from `[!contradiction]` to `[!note]`, reframed as explained), [[Cleric]] (Sacred Interposition note updated), [[Druid]] (Nature's Snare, Bestial Reflex, Reactive Disruption notes updated), [[FEARS MOC]] (cluster-wide summary updated)
- Key insight: **Ruled explained, not anomalous.** Cleric already has Divine Intervention as an established once-per-long-rest resource shape — Sacred Interposition follows that same cadence rather than arbitrarily bypassing the shared pool. Druid's whole reaction kit leans on Wild Shape as its resource identity instead of the generic PB pool — Bestial Reflex is directly gated on being in Beast Form, making the dependency explicit rather than coincidental. Reframes two of [[Class Reactions]]' six pool-exception classes from "open contradiction" to "resolved, consistent with class design" — [[Monk]], [[Investigator]], [[Wizard]], and [[Inventor]]'s remaining exceptions are still unexplained.
- Note: no manifest entry (no `.raw/` source involved) — this is a ruling clarifying existing ingested content, not new content.

## [2026-07-12] ruling | Bender's Elemental Rebirth confirmed intentional
- Source: user ruling, given directly in conversation
- Summary: resolved whether [[Bender]]'s Elemental Rebirth (the sole Last Stand option that doesn't result in permanent death) is an intentional exception, a transcription error, or evidence the "permanent death" framing itself is wrong
- Pages updated: [[Bender]] (added the level-1 reversion detail to Elemental Rebirth's effect text, replaced the `[!contradiction]` callout with a `[!note]` confirming intentional design), [[Last Stand]] (same reversion detail + callout downgrade in the shared-rules section and the Bender per-class table), [[FEARS MOC]] (cluster-wide summary updated)
- Key insight: **Ruled intentional** — the elemental-transformation flavor justifies surviving Last Stand, but reforming at 1st level acts as a soft-retirement mechanism: mechanically severe enough that most players will still choose permanent death or genuine retirement over restarting the character from scratch. Not a documentation error, and not grounds to soften the hub page's "permanently dies, cannot be returned" framing — that stays the default, with this as its one confirmed carve-out.
- Note: no manifest entry (no `.raw/` source involved) — this is a house-rule addition on top of the original ingested content.

## [2026-07-12] ruling | Last Stand DC-base + Sorcerer gap closure
- Source: user ruling, given directly in conversation (not a `.raw/` ingest)
- Summary: resolved two of the open questions the post-ingest lint/review pass surfaced across the 24-class FEARS roster — (1) which source wins when a class's per-class deep-dive conflicts with the older DCS-era summary, and (2) the three-way Last Stand DC-base split
- Pages updated: [[Last Stand]] (Sorcerer's gap closed with a new 3-option table — Arcane Cataclysm, Well of Power, Wild Surge Unleashed; DC-base resolved to canonical `10+PB+ability`; corrected Barbarian/Monk/Paladin×2/Rogue's `12+PB+ability` and Reaper's `8+PB+ability` entries; fixed a pre-existing mislabel attributing Barbarian's "Last Laugh" to Bender), [[Sorcerer]] (added the same Last Stand table, flagged as GM-provided rather than source-derived), [[Barbarian]], [[Monk]], [[Paladin]], [[Rogue]], [[Reaper]] (DC corrections on each class's own Last Stand table to match), [[FEARS MOC]] (cluster-wide summary updated to reflect both resolutions)
- Key insight: **Ruling 1 — deep-dive/full class page is authoritative over the old condensed summary whenever they conflict.** Applies going forward to the five still-open [[Damage Reduction]] contradictions (Barbarian, Monk, Paladin, Ranger, Shaman), the [[Weapon Mastery]] table conflicts (Tattooist, Shaman), and the [[Evasion]] Ranger conflict — not yet applied to those pages as of this entry, pending the rest of the open-questions pass. **Ruling 2 — Sorcerer's missing Last Stand section was a genuine design gap, not a documentation artifact**, closed with new content rather than left as a permanent absence. **Ruling 3 — Last Stand's canonical DC base is `10+PB+ability`**; every deviation was a transcription error, not intentional per-class variance. Still open: whether Bender's Elemental Rebirth (survives Last Stand instead of dying) is an intentional exception or a miscategorization.
- Note: this entry documents rulings applied across multiple pages in one pass, not a single-source ingest — no manifest entry created (no `.raw/` source involved).

## [2026-07-12] ingest | Wizard
- Source: `.raw/Wizard.md`
- Summary: upgraded [[Wizard]] in place (full detail) — **the 24th and final class in the FEARS per-class deep-dive pass**
- Pages created: none
- Pages updated: [[Wizard]] (fully rewritten — full level table, Spellbook/Arcane Recovery/Spell Mastery suite, Last Stand, Class Reactions), [[Last Stand]] (Wizard's 3 options, 23rd confirming class of 24 ingested, second plain-8-base DC data point), [[Class Reactions]] (Wizard's 3-reaction table, 24th and final confirming class, fourth pool-bypass exception shape), [[Momentum]] (final class-specific gain source — Arcane Flow — with a flagged copy-paste error in its own feature text), [[Weapon Mastery]] (explicit denial, twice over, matching Sorcerer's shape), [[FEARS MOC]] (major update — marks all 24/24 classes complete, adds a cluster-wide patterns summary), [[index]], [[hot]]
- Key insight: The final per-class deep-dive. Twenty-third confirmation of [[Last Stand]] (of 24 ingested — Sorcerer remains the sole non-confirming source), with Null Field's plain `8+PB+INT` DC becoming the **second** confirmed instance of that base after Reaper — upgrading it from a one-off curiosity to a real recurring (if minority) pattern. Twenty-fourth and final confirmation of [[Class Reactions]], with Counterspell Instinct joining the small set of confirmed pool-bypass exceptions, notable as the only one explained in-text by a specific named feature (Magic Sense) rather than a bare rule. Nineteenth confirmation of the `8+PB+ability mod` formula, with zero contradictions across all 24 classes — the most airtight universal rule this cluster produced. One amusing documentation error: Magic Sense's own text says "cast a Bender spell" where the class's intro correctly says "a spell" — an apparent copy-paste leftover from another class's document. **With this ingest, all 24 FEARS classes have now been through a complete per-class deep-dive.** Updated FEARS MOC with a consolidated cluster-wide-patterns summary covering the DC formula, Last Stand's three-way DC split, Class Reactions' four exception shapes, Weapon Mastery's fully-verified Non-Martials list, the five accumulated Damage Reduction contradictions, and the handful of internal documentation quirks found along the way.
- Note: no new address allocated (reused c-000066). **0 per-class deep-dive files remain — the FEARS class roster is fully documented.**

## [2026-07-12] ingest | Witch
- Source: `.raw/Witch.md`
- Summary: upgraded [[Witch]] in place (full detail)
- Pages created: none
- Pages updated: [[Witch]] (fully rewritten — full level table, Malefic Touch/Witches Mark/Hex Contagion suite, Last Stand, Class Reactions), [[Last Stand]] (Witch's 3 options, 22nd confirming class of 23 ingested), [[Class Reactions]] (Witch's 3-reaction table, 23rd confirming class, two overlapping-shape reactions), [[Momentum]] (new gain source — Hex Momentum), [[Weapon Mastery]] (third confirming silence), [[Damage Reduction]] (flags "Hex of Frailty" as unconfirmed rather than contradicted — Coven features aren't detailed in this source), [[FEARS MOC]], [[index]], [[hot]]
- Key insight: Twenty-third per-class deep-dive, twenty-second confirmation of [[Last Stand]] (of 23 ingested — Sorcerer remains the sole non-confirming source) and twenty-third of [[Class Reactions]], both clean. Eighteenth confirmation of the `8+PB+ability mod` formula. Notable non-finding: the existing "Hex of Frailty" DR claim is neither confirmed nor contradicted — the deep-dive is silent on it, but also never details Coven-specific features where it may live, so it's flagged as an open unconfirmed claim rather than folded into this session's run of outright DR contradictions. **With Witch done, only Wizard remains uningested among all 24 FEARS classes.**
- Note: no new address allocated (reused c-000022). 1 per-class deep-dive file remains (Wizard).

## [2026-07-12] ingest | Warlock
- Source: `.raw/Warlock.md`
- Summary: upgraded [[Warlock]] in place (full detail)
- Pages created: none
- Pages updated: [[Warlock]] (fully rewritten — full level table, Pact Magic/Eldritch Blast/Invocation suite, Last Stand, Class Reactions), [[Last Stand]] (Warlock's 3 options, 21st confirming class of 22 ingested), [[Class Reactions]] (Warlock's 3-reaction table, 22nd confirming class, clean), [[Momentum]] (new shape — Darkness Veil grants Momentum to the protected target, not the caster), [[Called Shot]] (new access route — Chaos Shot invocation), [[Injury System]] (twelfth hook — standard downgrade, notable for a reused feature name), [[Weapon Mastery]] (second confirming silence, consistent with existing Non-Martials listing), [[FEARS MOC]], [[index]], [[hot]]
- Key insight: Twenty-second per-class deep-dive, back to standard format. Twenty-first confirmation of [[Last Stand]] (of 22 ingested — Sorcerer remains the sole non-confirming source) and twenty-second of [[Class Reactions]], both clean. Seventeenth confirmation of the `8+PB+ability mod` formula. No major contradictions this ingest — mostly clean confirmations plus two new mechanic shapes (Darkness Veil's ally-directed Momentum grant, Chaos Shot's Called Shot hook) and a minor internal naming quirk (the feature name "Eldritch Resilience" reused for two unrelated ability suites at 9th and 15th level).
- Note: no new address allocated (reused c-000068). 2 per-class deep-dive files remain.

## [2026-07-12] ingest | Warden
- Source: `.raw/Warden.md`
- Summary: upgraded [[Warden]] in place (full detail, including all four Disciplines)
- Pages created: none
- Pages updated: [[Warden]] (fully rewritten — full level table, Natural Power/Prime Element/Discipline suite, Last Stand, Class Reactions), [[Momentum]] (richest single-class Momentum documentation this session — four innate triggers plus a per-Discipline fifth), [[Damage Reduction]] (three new clean DR hooks — Stone Skin, Unyielding Terrain, Sentinel's Anchor), [[Injury System]] (eleventh hook — Glacial Endurance, first to act before an Injury save triggers), [[Called Shot]] (new access route — Predator's Mark/Pursuit, Prey-gated), [[Weapon Mastery]] (Full Martials confirmed a sixth time, though the grant lands at 3rd level not 1st), [[Last Stand]] (Warden's 3 options, 20th confirming class of 21 ingested, new DC-less save gap), [[Class Reactions]] (Warden's 3-reaction table, 21st confirming class, a 2-use reaction), [[Evasion]] (three new situational Evasion bonuses), [[FEARS MOC]], [[index]], [[hot]]
- Key insight: Twenty-first per-class deep-dive, twentieth confirmation of [[Last Stand]] (of 21 ingested — Sorcerer remains the sole non-confirming source) and twenty-first of [[Class Reactions]] (clean, though Primal Retribution costs 2 pool uses like Sangromancer's Blood Transfusion). Sixteenth confirmation of the `8+PB+ability mod` formula. Standout finding: The Earth Remembers names a save type for all five Prime Element variants but never once gives a DC formula — a first for this cluster's Last Stand options. Also standout: Glacial Endurance is the first Injury hook to act proactively, spending a Power Die to prevent an Injury save from triggering at all rather than softening its outcome afterward. Warden's core chassis alone carries four independent Momentum triggers, the richest single-class Momentum integration seen this session.
- Note: no new address allocated (reused c-000049). 3 per-class deep-dive files remain.

## [2026-07-12] ingest | Tattooist
- Source: `.raw/Tattooist.md`
- Summary: upgraded [[Tattooist]] in place (full detail)
- Pages created: none
- Pages updated: [[Tattooist]] (fully rewritten — full level table, Spellbanger/Tattoo/Style suite, Last Stand, Class Reactions), [[Weapon Mastery]] (new contradiction — explicit "no Weapon Mastery" statement vs. existing Half-Martials listing), [[Momentum]] (two new gain sources — Etched Flow, Bad Ink), [[Damage Reduction]] (new clean hook — Inscribed Ward, mapped onto DCS body locations), [[Called Shot]] (new access route — Anatomical Precision, plus reverse Evasion-defense interactions), [[Injury System]] (tenth hook — Inked Resilience, first to combine downgrade + Momentum-ignore), [[Evasion]] (novel reaction — Inkguard's retroactive hit-to-miss conversion), [[Last Stand]] (Tattooist's 3 options, 19th confirming class of 20 ingested), [[Class Reactions]] (Tattooist's 3-reaction table, 20th confirming class, spellbanger-layered), [[FEARS MOC]], [[index]], [[hot]]
- Key insight: Twentieth per-class deep-dive, back to standard format after Sorcerer's divergence. Nineteenth class confirming Last Stand (Sorcerer remains the sole non-confirming source of 20) and twentieth confirming Class Reactions (spellbanger-layered, a fourth class this session with resource-layered reactions). Fifteenth confirmation of the `8+PB+ability mod` formula, first on Constitution. The standout finding is stronger than a typical gap: the source explicitly denies having Weapon Mastery, directly contradicting an existing table entry rather than just omitting the subsystem. Inked Resilience is the first Injury hook to merge two previously-separate shapes (downgrade + Momentum-ignore), and Inkguard is the first reaction to retroactively convert a hit into a miss.
- Note: no new address allocated (reused c-000020). 4 per-class deep-dive files remain.

## [2026-07-12] ingest | Sorcerer
- Source: `.raw/Sorcerer.md`
- Summary: upgraded [[Sorcerer]] in place (full detail)
- Pages created: none
- Pages updated: [[Sorcerer]] (fully rewritten — full level table, Font of Magic/Metamagic/Origin suite, format-outlier notes), [[Last Stand]] (flags the first-ever missing Last Stand section, confirmed count stays 18/24), [[Class Reactions]] (Sorcerer's 4 reactions documented despite no consolidated section, plus an internal pool-attribution inconsistency), [[Momentum]] (two new gain sources — Draconic Momentum, Avatar of Chaos's flat +3/turn — plus a new default-trigger-by-origin-theme design pattern), [[Weapon Mastery]] (explicit "no Weapon Mastery" statement, strongest Non-Martials confirmation yet), [[FEARS MOC]], [[index]], [[hot]]
- Key insight: Nineteenth per-class deep-dive, and the most structurally divergent source this session — an avatar-image header instead of a narrative quote, an explicit Weapon Mastery denial rather than a silence, a Universal Conversion Rules table for adapting any 5E Sorcerous Origin, a Momentum-trigger-by-origin-theme default table, and critically, **no Last Stand section at all**. This is the first per-class file (of 19) to omit Last Stand entirely, so its confirmed-universal count holds at 18/24 rather than advancing. Class Reactions are present in substance but never consolidated under one heading, and two of the four aren't stated as pool-users in their own text despite the source's summary table claiming otherwise — an internal inconsistency, not a cross-source one. Fourteenth confirmation of the `8+PB+ability mod` formula.
- Note: no new address allocated (reused c-000067). 5 per-class deep-dive files remain.

## [2026-07-12] ingest | Shaman
- Source: `.raw/Shaman.md`
- Summary: upgraded [[Shaman]] in place (full detail)
- Pages created: none
- Pages updated: [[Shaman]] (fully rewritten — full level table, Totems/Spirituality suite, Last Stand, Class Reactions), [[Momentum]] (two new gain sources — Totemic Rhythm, Spirit-Touched Ground), [[Damage Reduction]] (new contradiction — Totemic Resilience's flat self-only DR vs. existing "elemental DR to allies" claim), [[Weapon Mastery]] (new unresolved gap — Shaman listed Half-Martial but no mastery feature in source), [[Called Shot]] (new access route — Ancestral Precision, grants advantage rather than reducing penalty), [[Evasion]] (two new alternate DC formulas tied to Sacred Focus/Totem choice), [[Last Stand]] (Shaman's 3 options, 18th class, two more 10-base DC data points), [[Class Reactions]] (Shaman's 3-reaction table, 18th class, clean pool confirmation plus an internal table/heading mismatch), [[FEARS MOC]], [[index]], [[hot]]
- Key insight: Eighteenth per-class deep-dive, eighteenth confirmation of [[Last Stand]] (no exception) and [[Class Reactions]] (clean, no exceptions). Thirteenth confirmation of the `8+PB+ability mod` formula. Fourth DR-related DCS-summary contradiction this session (Totemic Resilience vs. the old "elemental DR to allies" claim). Genuinely new gap: Shaman is a listed Half-Martial in Weapon Mastery's table, yet its own deep-dive never mentions the subsystem at all — unresolved, distinct from Sangromancer's confirming silence last ingest. Second class with two independent self-directed Momentum triggers. Flagged (not resolved) a source-internal inconsistency: Totemic Shield's own section heading says 5th level, but the level table's 5th-level row omits it.
- Note: no new address allocated (reused c-000018). 6 per-class deep-dive files remain.

## [2026-07-12] ingest | Sangromancer
- Source: `.raw/Sangromancer.md`
- Summary: upgraded [[Sangromancer]] in place (full detail)
- Pages created: none
- Pages updated: [[Sangromancer]] (fully rewritten — full level table, Sanguine Casting/Vitae Strain suite, Last Stand, Class Reactions), [[Momentum]] (new gain source — Sanguine Momentum, first amount-gated trigger), [[Injury System]] (two new hook shapes — Blood Resilience's save-advantage, Safe Bloodletting's self-harm immunity), [[Corruption]] (new parallel-but-distinct system — Vitae Strain), [[Weapon Mastery]] (Non-Martials listing confirmed by omission), [[Last Stand]] (Sangromancer's 3 options, 17th class, fourth distinct DC shape), [[Class Reactions]] (Sangromancer's 3-reaction table, 17th class, HP-layered), [[FEARS MOC]], [[index]], [[hot]]
- Key insight: Seventeenth per-class deep-dive, seventeenth confirmation of [[Last Stand]] (no exception, but Crimson Cataclysm's DC scales off Vitae Strain total — a fourth distinct DC shape) and [[Class Reactions]] (HP-layered, third class with this heavy-resource-stacking pattern). Twelfth confirmation of the `8+PB+ability mod` formula, third on an Intelligence-based caster. The standout finding is Vitae Strain itself — a six-threshold accumulation track structurally identical to Corruption's shape, but the source explicitly states it's a distinct stat, not terminology drift like Bender's "Corruption Point." Confirms Weapon Mastery's Non-Martials list by simple absence of any Weapon Mastery feature in the document.
- Note: no new address allocated (reused c-000016). 7 per-class deep-dive files remain.

## [2026-07-12] ingest | Rogue
- Source: `.raw/Rogue.md`
- Summary: upgraded [[Rogue]] in place (full detail)
- Pages created: none
- Pages updated: [[Rogue]] (fully rewritten — full level table, Sneak Attack/Cunning Action suite, Last Stand, Class Reactions), [[Momentum]] (genuine reset-rule exception — Slippery Escape overrides Disengage's Momentum reset — plus two new gain sources and a third self-directed loss-mitigation instance), [[Evasion]] (naming-collision note — Rogue's own "Evasion" feature is the unrelated D&D-legacy save mechanic), [[Called Shot]] (new access route — Perfect Shot, full penalty waiver), [[Injury System]] (seventh downgrade-adjacent hook — Nerve-Steeled, first Momentum-specific Injury carve-out), [[Weapon Mastery]] (Full Martials confirmed a fifth time), [[Last Stand]] (Rogue's 3 options, 16th class, fourth 12-base DC data point), [[Class Reactions]] (Rogue's 4-reaction table, 16th class, clean pool confirmation), [[FEARS MOC]], [[index]], [[hot]]
- Key insight: Sixteenth per-class deep-dive, sixteenth confirmation of [[Last Stand]] (no exception) and [[Class Reactions]] (clean, no exceptions). The standout finding: Slippery Escape is a genuine, named class-specific exception to Momentum's core "Disengage resets to 0" rule — not a contradiction to flag, a deliberate carve-out. Two new Momentum gain sources (Cunning Flow's +2-on-Sneak-Attack, Shadow Slip's +1-on-enemy-miss) and a third self-directed loss-mitigation instance (Sneak Attack Stability, after Magus's Adaptive Mind). The long-standing Exploit Weakness/Exploit Vulnerability naming collision with Investigator remains unresolved — this source never uses the term "Exploit Weakness" at all. Also clarified: Rogue's own 6th-level "Evasion" feature is the classic D&D save-based ability, unrelated to FEARS's own Evasion combat-defense system despite the shared name.
- Note: no new address allocated (reused c-000063). 8 per-class deep-dive files remain.

## [2026-07-12] ingest | Reaper
- Source: `.raw/Reaper.md` (1237 lines, the largest source ingested this session)
- Summary: upgraded [[Reaper]] in place (full detail, including full Covenant subclasses)
- Pages created: none
- Pages updated: [[Reaper]] (fully rewritten — full level table, Soul Harvest/Reaper's Strike suite, all three Covenants in full detail, Last Stand, Class Reactions, systems-integration cross-links), [[Last Stand]] (Reaper's 3 options, 15th class, new third DC base), [[Class Reactions]] (Reaper's 4 base + 2 Covenant reactions, 15th class, heavy Soul Token layering), [[Momentum]] (new gain source — Soul Shield full-negation — plus a flagged naming/level inconsistency within the source itself), [[Called Shot]] (new access route — token-costed, first of its kind), [[Damage Reduction]] (new token-conditional DR hook — Death's Resilience), [[Weapon Mastery]] (Full Martials confirmed a fourth time, plus a new scheduled-mastery-grant detail), [[Corruption]] (new gain triggers, Death's Taint tiers map onto existing thresholds), [[FEARS MOC]], [[index]], [[hot]]
- Key insight: Fifteenth per-class deep-dive, fifteenth confirmation of [[Last Stand]] (no exception, but a genuinely new third DC base — plain `8+PB+ability`, distinct from the existing 10- and 12-base patterns) and [[Class Reactions]] (heavily layered with Soul Token costs on every single reaction, the same resource-stacking shape as Magus's spell-slot reactions). By far the richest single source this session — the only per-class file with fully detailed subclasses (three complete Covenants, four tiers each) rather than a placeholder. New token-conditional DR hook, new token-costed Called Shot route, new Momentum trigger, new Corruption gain triggers whose tier bands cleanly map onto the existing 5/10/15/20 thresholds. Flagged (not resolved) an internal documentation inconsistency: the source names the same Momentum-on-harvest mechanic two different ways at two different levels in two different sections of itself. Skipped non-mechanical roleplaying/sample-build/multiclassing content as out of wiki scope.
- Note: no new address allocated (reused c-000050). 9 per-class deep-dive files remain.

## [2026-07-12] ingest | Ranger
- Source: `.raw/Ranger.md`
- Summary: upgraded [[Ranger]] in place (full detail)
- Pages created: none
- Pages updated: [[Ranger]] (fully rewritten — full level table, Hunter's Mark/Favoured Enemy/Claimed Ground suite, Last Stand, Class Reactions), [[Damage Reduction]] (new contradiction — Hunter's Mark's flat -2 DR vs. existing "WIS mod" claim — plus new Fleet Guard hook), [[Evasion]] (new contradiction — Favoured Enemy Agility grants advantage, not "+WIS mod"), [[Momentum]] (two new gain sources — Favoured Enemy hits, Claimed Ground's Territorial Momentum), [[Weapon Mastery]] (Full Martials row confirmed zero drift a third time), [[Last Stand]] (Ranger's 3 options, 14th class, no explicit DC in any option), [[Class Reactions]] (Ranger's 3-reaction table, 14th class, clean pool confirmation), [[FEARS MOC]], [[index]], [[hot]]
- Key insight: Fourteenth per-class deep-dive, fourteenth confirmation of [[Last Stand]] (no exception) and [[Class Reactions]] (clean, no exceptions, back-to-back with Paladin's). Sovereign Ground's WIS save DC (`8+PB+WIS`) is the eleventh confirmation of the `8+PB+ability mod` formula. Two new contradictions against the older DCS-level class-hook summaries: Hunter's Mark's DR reduction is flat -2 here (not WIS-scaled), and Favoured Enemy's Evasion bonus is advantage (not "+WIS mod"). With Barbarian's, Monk's, and Paladin's prior DR/Evasion conflicts, this makes four of fourteen classes whose deep-dive contradicts an early DCS-summary claim — worth treating any still-unconfirmed DCS-summary hook as provisional going forward, flagged explicitly on the MOC.
- Note: no new address allocated (reused c-000064). 10 per-class deep-dive files remain.

## [2026-07-12] ingest | Paladin
- Source: `.raw/Paladin.md`
- Summary: upgraded [[Paladin]] in place (full detail)
- Pages created: none
- Pages updated: [[Paladin]] (fully rewritten — full level table, Divine Smite/Aura/Channel Divinity suite, Last Stand, Class Reactions), [[Last Stand]] (Paladin's 3 options, 13th class, standard death clause + new DC-base split observation), [[Class Reactions]] (Paladin's 3-reaction table, 13th class, clean pool confirmation), [[Momentum]] (new exception — Righteous Stability — plus Ward of Faith confirmed verbatim-shared with Cleric), [[Called Shot]] (new access route — Holy Precision — plus Judgment confirmed verbatim-shared with Cleric), [[Damage Reduction]] (new contradiction — Aura of Protection is saves-only, not DR), [[Weapon Mastery]] (Full Martials row confirmed zero drift a second time), [[FEARS MOC]], [[index]], [[hot]]
- Key insight: Thirteenth per-class deep-dive, thirteenth confirmation of [[Last Stand]] (no exception) and [[Class Reactions]] (clean, no exceptions — a nice contrast right after Monk's total departure). Radiant Judgment's CON save DC (`8+PB+CHA`) is the tenth confirmation of the `8+PB+ability mod` formula. Biggest finding: Paladin's Ward of Faith and Judgment (via Channel Divinity) are word-for-word identical to Cleric's abilities of the same names — first confirmed verbatim ability-share between two classes. New contradiction: Aura of Protection is entirely a saving-throw bonus here, conflicting with Damage Reduction's existing "Aura = CHA mod DR" claim. Also surfaces an unresolved pattern: Last Stand DCs split between a 10-base and 12-base formula across different classes, not previously noticed. Notable gap: this source names "Spellcasting" as a feature but never gives its DC formula, the only per-class deep-dive to do this.
- Note: no new address allocated (reused c-000065). 11 per-class deep-dive files remain.

## [2026-07-12] ingest | Monk
- Source: `.raw/Monk.md`
- Summary: upgraded [[Monk]] in place (full detail)
- Pages created: none
- Pages updated: [[Monk]] (fully rewritten — full level table, Ki Techniques/Flow suite, Last Stand, Class Reactions), [[Last Stand]] (Monk's 3 options, 12th class, standard death clause reaffirmed), [[Class Reactions]] (Monk's 3-reaction table, cleanest total pool departure — all Focus, not PB), [[Damage Reduction]] (new contradiction — flat level-gated DR vs. existing ½-DEX-mod formula), [[Evasion]] (new formula — WIS mod, not DEX, from Unarmoured Defence), [[Called Shot]] (new access route — Deadeye Strike), [[Injury System]] (sixth downgrade-adjacent hook — Serene Focus, new effect-suppression shape), [[Weapon Mastery]] (flags open question — Ki Flow vs. Flow Strike, never confirmed as the same mechanic), [[Momentum]] (Balanced Rhythm reconfirmed zero drift, Ki Flow cross-link), [[FEARS MOC]], [[index]], [[hot]]
- Key insight: Twelfth per-class deep-dive, twelfth confirmation of [[Last Stand]] (no exception). [[Class Reactions]] confirmed a twelfth time but with the cleanest total departure from the shared pool yet — all three reactions cost Focus, while the source's own header still claims the PB pool, an apparent internal inconsistency. Technique Save DC (`8+PB+WIS`) is the ninth confirmation of the `8+PB+ability mod` formula and the second on a non-caster. New contradiction: Unarmoured Resilience's flat DR (1/2/3) conflicts with Damage Reduction's existing "½ DEX mod" Monk formula — same treatment as Barbarian's Rage DR conflict. Genuinely open thread: this source's "Ki Flow" (turn-start TP regen at high Momentum) never mentions "Flow Strike" by name, the on-hit mechanic Weapon Mastery System claims Monk/Bender share — not resolved as same-or-different.
- Note: no new address allocated (reused c-000062). 12 per-class deep-dive files remain.

## [2026-07-12] ingest | Magus
- Source: `.raw/Magus.md`
- Summary: upgraded [[Magus]] in place (full detail)
- Pages created: none
- Pages updated: [[Magus]] (fully rewritten — full level table, Spellstrike/Spell Combat suite, War Tradition, Last Stand, Class Reactions), [[Last Stand]] (Magus's 3 options, 11th class, standard death clause reaffirmed), [[Class Reactions]] (Magus's 3-reaction table, 11th class, heaviest spell-slot resource-layering yet), [[Momentum]] (new gain source — Spellstrike — plus a second Momentum-loss-mitigation reaction, Adaptive Mind, self-directed this time), [[Damage Reduction]] (clarifies Arcane Guard's DR value as flat rather than "scaling"), [[FEARS MOC]], [[index]], [[hot]]
- Key insight: Eleventh per-class deep-dive, eleventh confirmation of [[Last Stand]] (no exception) and [[Class Reactions]] (all three reactions layer a spell slot on top of the shared PB pool — the heaviest resource-stacking seen yet). Spell Save DC (`8+PB+INT`) is the eighth confirmation of the `8+PB+ability mod` formula. Adaptive Mind mirrors Cleric's Ward of Faith exactly but protects the Magus rather than an ally — first self-directed instance of that Momentum-loss-mitigation shape. Minor clarification (not contradiction): Arcane Guard's DR is a flat +1 per point spent, sharpening the older DCS-summary's vaguer "scaling DR" framing.
- Note: no new address allocated (reused c-000013). 13 per-class deep-dive files remain.

## [2026-07-12] ingest | Investigator
- Source: `.raw/Investigator.md`
- Summary: upgraded [[Investigator]] in place (full detail)
- Pages created: none
- Pages updated: [[Investigator]] (fully rewritten — full level table, Exploit Vulnerability/Exploit Weakness suite, Finisher, Last Stand, Class Reactions), [[Last Stand]] (Investigator's 3 options, 10th class, standard death clause reaffirmed), [[Class Reactions]] (Investigator's 3-reaction table, 10th class, third partial pool exception via Predictive Step), [[Momentum]] (new gain source — Exploit Momentum), [[Called Shot]] (new access route — Forensic Called Shot, Quarry-gated version of Fighter's Surgical Precision), [[Injury System]] (fifth downgrade class hook — Foreseen Harm, first self-only), [[FEARS MOC]], [[index]], [[hot]]
- Key insight: Tenth per-class deep-dive, tenth confirmation of [[Last Stand]] (no exception). [[Class Reactions]] confirmed a tenth time, with Predictive Step as a third partial pool exception (own INT-mod-per-long-rest budget), same shape as Cleric's Sacred Interposition but on a martial class. Death Throes Denial's CON save DC (`8+INT+PB`) is the seventh confirmation of the `8+PB+ability mod` formula and the first on a non-caster — the formula now spans casters and martials alike. Confirms the long-standing Exploit Weakness/Exploit Vulnerability naming collision with [[Rogue]] remains unresolved (this source uses both names for two different Investigator features, doesn't address the cross-class overlap).
- Note: no new address allocated (reused c-000011). 14 per-class deep-dive files remain.

## [2026-07-12] ingest | Inventor
- Source: `.raw/Inventor.md`
- Summary: upgraded [[Inventor]] in place (full detail)
- Pages created: none
- Pages updated: [[Inventor]] (fully rewritten — full level table, Specialisation/Upgrades suite, Wondrous Item progression, Last Stand, Class Reactions), [[Last Stand]] (Inventor's 3 options, 9th class, standard death clause reaffirmed), [[Class Reactions]] (Inventor's 3-reaction table, 9th class, first confirmed 7th-level gate), [[Momentum]] (new flat enemy-Momentum-loss trigger from Infusion Burst), [[Damage Reduction]] (new class hook — Engineered Guard — plus Overclock's DR-reduction reaction), [[Weapon Mastery]] (Full Martials row confirmed zero drift), [[FEARS MOC]], [[index]], [[hot]]
- Key insight: Ninth per-class deep-dive, ninth confirmation of [[Last Stand]] (no exception). [[Class Reactions]] confirmed a ninth time too, but gated to 7th level — the latest unlock of any class so far, worth watching as a possible half-caster pattern. Spell Save DC (`8+PB+INT`) is the sixth confirmation of the `8+PB+ability mod` formula and the first on an Intelligence-based caster. Infusion Burst's attacker-loses-1-Momentum trigger is a genuinely new interaction shape — a flat enemy-side loss, distinct from Cleric's ally-loss-mitigation and Bard's enemy-gain-reduction. Weapon Mastery System's Full Martials row (Inventor already listed there) confirmed with zero drift by an independent source.
- Note: no new address allocated (reused c-000012). 15 per-class deep-dive files remain.

## [2026-07-12] ingest | Fighter
- Source: `.raw/Fighter.md`
- Summary: upgraded [[Fighter]] in place (full detail)
- Pages created: none
- Pages updated: [[Fighter]] (fully rewritten — full level table, Martial Actions, Weapon Mastery, Action Surge, Last Stand, Class Reactions), [[Last Stand]] (Fighter's 3 options, 8th class, standard death clause reaffirmed), [[Class Reactions]] (Fighter's 3-reaction table, 8th class, cleanest shared-pool confirmation yet), [[Momentum]] (new gain source — Action Surge, the least-conditional trigger seen — plus a second confirmed reset-to-+1 instance from Rush of Adrenaline), [[Called Shot]] (new access route — Surgical Precision, the first hook that flips a penalty into a net bonus), [[Evasion]] (Agile Defence and Shield Master Fighting Styles feed directly into Evasion), [[Weapon Mastery]] (Fighter's multi-mastery mechanic and 1-crit progression confirmed with zero drift), [[FEARS MOC]], [[index]], [[hot]]
- Key insight: Eighth per-class deep-dive, eighth confirmation of [[Last Stand]] (no exception) and [[Class Reactions]] — and the cleanest confirmation of the latter's shared-PB-pool default seen yet, a useful counterweight right after Druid's total departure from that pattern. Rush of Adrenaline's Momentum reset to +1 upgrades Druid's Wild Shape reset from a one-off curiosity to a genuine recurring interaction type. Lowest self-rated complexity of any class this session (2/10), consistent with its "reliable, no complex resource pools" design intent. No Injury System, Corruption, or Sanity/Focus content in this source — expected for a non-caster with no mental-triad ties.
- Note: no new address allocated (reused c-000061). 16 per-class deep-dive files remain.

## [2026-07-12] ingest | Druid
- Source: `.raw/Druid.md`
- Summary: upgraded [[Druid]] in place (full detail)
- Pages created: none
- Pages updated: [[Druid]] (fully rewritten — full level table, Wild Shape/Beast Form suite, Nature's Remembrance, Last Stand, Class Reactions), [[Last Stand]] (Druid's 3 options, 7th class, standard death clause reaffirmed), [[Class Reactions]] (Druid's reaction table + a deeper pool exception — none of its three reactions use the shared pool), [[Momentum]] (two new gain sources — Primal Shift, Nature's Remembrance — plus a new "reset to +1" interaction type from Wild Shape), [[Damage Reduction]] (baseline Beast Form DR formula, distinct from the existing Circle of the Moon bonus), [[Evasion]] (Beast Form Evasion formula), [[Sanity]] (Natural Anchor's save-advantage + recovery hook, Primal Dissolution's DC 12 save), [[Focus]] (first exact Focus-concentration formula, `1d20+WIS`, and Draw Power's Focus spend), [[FEARS MOC]], [[index]], [[hot]]
- Key insight: Seventh per-class deep-dive, seventh confirmation of [[Last Stand]] (no exception) and sixth-plus of [[Class Reactions]] — though Druid's version is the deepest break from the shared-pool pattern seen yet: all three of its reactions run independent budgets, not just one exception like Cleric's Sacred Interposition. Spell Save DC (`8+PB+WIS`) is the fifth independent confirmation of the `8+PB+ability mod` formula. Full Beast Form DCS integration is a first: its own Evasion and DR formulas, plus a genuinely new Momentum interaction (Wild Shape resets Momentum to +1, neither a gain, loss, nor zero-reset). Draw Power and the Concentration check both tie directly into the [[Focus]] pool, the latter finally giving an exact roll formula for what Bender and Binder only gestured at.
- Note: no new address allocated (reused c-000069). 17 per-class deep-dive files remain.

## [2026-07-12] ingest | Cleric
- Source: `.raw/Cleric.md`
- Summary: upgraded [[Cleric]] in place (full detail)
- Pages created: none
- Pages updated: [[Cleric]] (fully rewritten — full level table, Channel Divinity suite, Heroic/Epic Boons, Last Stand, Class Reactions), [[Last Stand]] (Cleric's 3 options, 6th class, standard death clause reaffirmed), [[Class Reactions]] (Cleric's 4-reaction table, 6th class, plus Sacred Interposition's pool-bypass exception), [[Called Shot]] (new access route — Judgment grants a penalty-free Called Shot via Channel Divinity), [[Momentum]] (new loss-side hook — Ward of Faith reduces an ally's Momentum loss), [[Injury System]] (fourth downgrade class hook — Mercy of the Divine, uniquely negates a Minor Injury outright), [[Corruption]] (new rougher "typically 8+" threshold from Turn the Profane Expanded), [[FEARS MOC]], [[index]], [[hot]]
- Key insight: Sixth per-class deep-dive, sixth confirmation of [[Last Stand]] (no exception this time) and [[Class Reactions]] — but Class Reactions gets its second genuine pool exception (Sacred Interposition, once/long rest, not limited by the shared pool), mirroring the shape of Bender's Last Stand exception. Spell Save DC (`8+PB+WIS`) is the fourth independent confirmation of the `8+PB+ability mod` formula. Confirms the existing Turn Undead enemy-morale hook (from the earlier Bloodied Breaking Points Rally ingest) as the formal ability Turn the Profane, with full mechanics now on-page.
- Note: no new address allocated (reused c-000070). This ingest's wiki content was written in a prior session turn but the manifest/log/hot-cache/MOC bookkeeping was left incomplete — closed out now without re-processing the source. 18 per-class deep-dive files remain.

## [2026-07-12] ingest | Binder
- Source: `.raw/Binder.md` (47KB, the largest source file ingested this session)
- Summary: upgraded [[Binder]] in place (full detail)
- Pages created: none
- Pages updated: [[Binder]] (fully rewritten — full Bound Remnants list, all four Binding Orders, Last Stand, Class Reactions), [[Weapon Mastery]] (resolves the old "Binder's Weapon Mastery profile unknown" gap with strong evidence of non-participation), [[Whisper Points]] (new gain trigger), [[Focus]] (third Focus-Save-adjacent data point), [[Momentum]] (first total absence, flagged as observation), [[Class Reactions]] (Binder's 3-reaction table, 5th class), [[Last Stand]] (Binder's 3 options, 5th class, standard death clause reaffirmed), [[FEARS MOC]], [[index]], [[hot]]
- Key insight: Fifth per-class deep-dive, fifth confirmation of [[Last Stand]] and [[Class Reactions]]. Source frontmatter reads `status: draft` — a value not seen on any other per-class file (others are `revised`, three corrected `excluded`) — flagged but not treated as excluded absent further signal. Resolves a genuinely old open question: Binder was never listed in [[Weapon Mastery System]]'s class-tier table, and this deep-dive's total silence on Weapon Mastery (no mastered weapon, all Remnant abilities are spell attacks) strongly suggests Binder simply doesn't use the subsystem, rather than the profile being merely undiscovered. Binding Save DC (`8+PB+CHA`) is the third independent confirmation of the `8+PB+ability mod` formula, extending it beyond spellcasting DCs specifically. First class with zero Momentum mention at all, despite Bleed Points' gain triggers structurally mirroring Momentum's — flagged as a parallel-system observation, not a contradiction. Full Binding Orders (4, each with 4 complete features) and Bound Remnants (17, each with Trait+Active) kept on-page per the established precedent from Bender's Disciplines, rather than split into separate pages.
- Note: no new address allocated (reused c-000057). 19 per-class deep-dive files remain.

## [2026-07-12] ingest | Bender
- Source: `.raw/Bender.md`
- Summary: upgraded [[Bender]] in place (full detail)
- Pages created: none
- Pages updated: [[Bender]] (substantially expanded), [[Momentum]] (two new gain sources from Elemental Flow), [[Focus]] (Focus-check-for-concentration data point), [[Corruption]] (second class's gain triggers + Point/Score terminology note), [[Sanity]] (new "Trauma Point" unconfirmed term), [[Bard]] (spellcasting DC formula upgraded from "reasonable assumption" to "confirmed twice"), [[Class Reactions]] (Bender's 4-reaction table, "Reaction Points" naming confirmed), [[Last Stand]] (Bender's 3 options + the permanent-death exception), [[FEARS MOC]], [[index]], [[hot]]
- Key insight: Fourth per-class deep-dive, fourth confirmation of [[Last Stand]] and [[Class Reactions]]. Two genuinely new findings: (1) the caster spellcasting DC formula (`8+PB+ability mod`) is now independently confirmed a second time, upgraded from a reasonable assumption to a confirmed universal rule; (2) Bender's third Last Stand option, Elemental Rebirth, does NOT result in permanent death — it's gated by "once per character's lifetime" instead, the first confirmed exception to the otherwise-universal Last Stand death clause. Also the richest subclass treatment seen so far (4 full Bender Disciplines with complete 3rd/7th/15th/20th feature progressions, versus every other class's incomplete "such as" example lists). One notable non-contradiction: Weapon Mastery System's claim that Bender shares Monk's Technique Point resource is neither confirmed nor contradicted by this deep-dive, which simply never discusses Weapon Mastery — treated as an out-of-scope silence, not conflicting evidence.
- Note: no new address allocated (reused c-000051). 20 per-class deep-dive files remain.

## [2026-07-12] ingest | Apothecary
- Source: `.raw/Apothecary.md`
- Summary: upgraded [[Apothecary]] in place (full detail, per the new standard)
- Pages created: none
- Pages updated: [[Apothecary]] (substantially expanded), [[Momentum]] (Chemical Rush gain source), [[Injury System]] (Trauma Specialist — first outright-removal class hook), [[Corruption]] (first mechanical gain triggers), [[Class Reactions]] (Apothecary's 7-reaction table, the largest so far), [[Last Stand]] (Apothecary's 3 options), [[FEARS MOC]], [[index]], [[hot]]
- Key insight: Third per-class deep-dive, third confirmation of [[Last Stand]] and [[Class Reactions]] as universal (3/24 each). The richest cross-system-linking class page so far: Apothecary is revealed as the most Corruption-heavy class documented to date (four independent mechanical Corruption-gain triggers — Unstable Concoction mishaps, Emergency Protocol, Chemical Burn, Metamorphic Infusion), giving [[Corruption]] its first concrete gain mechanics beyond "repeated failures or forbidden acts." Also the first class hook that removes an Injury outright (Trauma Specialist, time+resource gated) rather than downgrading a tier like Paladin's and Bard's — extends [[Injury System]]'s class-hook pattern to three distinct approaches. Metamorphic Infusion notably risks Corruption for the *recipient* of the effect, not the actor — the first sighting of transferable Corruption risk. Anatomical Precision introduces a distinct thrown-concoction Called Shot variant, cross-linked to [[Called Shot]] without being merged into its main table.
- Note: no new address allocated (reused c-000052). 21 per-class deep-dive files remain.

## [2026-07-12] policy correction | Full class ability detail on per-class pages
- User feedback: initial [[Barbarian]] and [[Bard]] ingests used a "Selected class features by level" approach — condensing to the mechanically/cross-reference-interesting subset rather than including every named ability. User wants full detail: "I think its more maintaining all class abilities in detail." Confirmed scope via a follow-up question: retroactively expand both existing pages, not just apply forward.
- Pages updated: [[Barbarian]], [[Bard]] — both rewritten with every named class feature in full mechanical text (every level's abilities, not a curated subset), full level tables including previously-omitted ASI rows, Quick Build and class-basics sections retained. Synthesis elements (contradiction flags, cross-links, "confirmed zero drift" notes, hub-page links) kept — the change is about not dropping mechanical ability detail, not about abandoning cross-referencing.
- Note: no hash/manifest change needed — underlying `.raw/` source content is unchanged, this was a wiki-layer completeness correction. Standard now documented on [[FEARS MOC]] for the remaining 22 per-class ingests.

## [2026-07-12] ingest | Bard
- Source: `.raw/Bard.md`
- Summary: upgraded [[Bard]] in place; created [[Last Stand]], [[Class Reactions]]
- Pages created: [[Last Stand]], [[Class Reactions]]
- Pages updated: [[Bard]] (substantially expanded, same pattern as [[Barbarian]]), [[Barbarian]] (cross-linked to the new hub pages, editorial notes resolved), [[Momentum]] (Inspirational Momentum gain source), [[Injury System]] (Soothing Performance class hook), [[FEARS MOC]], [[index]], [[hot]]
- Key insight: Second per-class deep-dive confirms the two mechanics flagged as open questions last ingest — [[Last Stand]] and [[Class Reactions]] are universal per-class frameworks, not Barbarian-specific, since Bard independently has near-identical versions of both. Spun off into dedicated hub pages with growing per-class tables now that the pattern is confirmed (2/24), rather than repeating the same generic explanation on every class page. Also surfaces the first explicit spellcaster DC formula in this cluster (`8+PB+CHA` for both save DC and attack modifier) — confirmed for Bard, a reasonable working assumption for other casters given the matching `8+PB+ability mod` shape used everywhere else, but not yet independently confirmed elsewhere. Confirms and generalizes the existing page's "Cutting Words reduces Enemy Rally checks" note into its full general mechanic. New Momentum-gain source (Inspirational Momentum, ally-support triggered) and a second Injury-downgrade class hook (Soothing Performance, distinct tier band from Paladin's).
- Note: no new address allocated for [[Bard]] (reused c-000071); 2 new addresses for the hub pages (c-000102, c-000103). 22 per-class deep-dive files remain.

## [2026-07-12] ingest | Barbarian
- Source: `.raw/Barbarian.md`
- Summary: upgraded [[Barbarian]] in place
- Pages created: none
- Pages updated: [[Barbarian]] (substantially expanded: class basics, full 1-20 level table, Rage/Momentum confirmed zero-drift, Rage Stances, Weapon Mastery confirmed zero-drift, selected class features, Primal Path subclass note, Last Stand, Class Reactions), [[Damage Reduction]] (Rage DR contradiction flagged), [[FEARS MOC]], [[index]], [[hot]]
- Key insight: First of 24 per-class deep-dive ingests this session — establishes the pattern going forward (in-place upgrade of the existing class page, same convention as the DCS-companion sources). Two class features (Momentum interactions, Weapon Mastery crit-progression) independently confirmed with zero drift against already-ingested crunch sources — a good sign for how reliable these per-class files are likely to be overall. One real contradiction: this source's Rage DR (flat, level-gated: 1/2/3+CON mod max 5) doesn't match [[Damage Reduction]]'s confirmed "CON mod, doubled while Raging" — flagged with `[!contradiction]`, not resolved. Two genuinely new mechanics never seen before in this cluster: **Last Stand** (permanent-death capstone at 0 HP, three options) and **Class Reactions** (a PB-sized shared reaction pool with baseline class-specific reactions). Both are framed in Barbarian-specific language but structurally read like they could be universal per-class frameworks — flagged as an open question on [[FEARS MOC]] to check against the next per-class ingest rather than assumed either way. Also noted: "Path of Wild Fury" as an example subclass doesn't match the already-known "Path of the Bear," but the source's own "such as" phrasing means this isn't treated as a contradiction, just an incomplete list.
- Note: no new address allocated — reused [[Barbarian]]'s existing address (c-000060) per the idempotency/in-place-upgrade rule. 23 per-class deep-dive files remain uningested.

## [2026-07-12] correction | No Summoner.md file exists in .raw/
- User feedback: "Summoner is not a class, it is removed."
- Checked `.raw/` directory listing directly for the first time — confirmed no `Summoner.md` file exists and never did. Every ingest since [[Weapon Mastery System]]'s had been claiming, without verification, that a `Summoner.md` per-class deep-dive sat uningested in `.raw/` — an unverified extrapolation from Weapon Mastery System's in-text Summoner references, repeated across 7 log entries and multiple [[FEARS MOC]] lines without ever actually checking the directory.
- Pages updated: [[FEARS MOC]] (uningested-files line corrected, phantom Summoner.md claim removed and replaced with an explicit note)
- Note: [[Classes_Summary]] and [[Binder]]'s page already correctly stated Summoner was retired and replaced by Binder — that part was never wrong. The error was specifically inventing a still-uningested source file that doesn't exist. Prior log entries below retain their original "including Summoner.md" wording per the append-only convention; this entry is the correction of record. The 24 actual uningested per-class files: Apothecary, Barbarian, Bard, Bender, Binder, Cleric, Druid, Fighter, Inventor, Investigator, Magus, Monk, Paladin, Ranger, Reaper, Rogue, Sangromancer, Shaman, Sorcerer, Tattooist, Warden, Warlock, Witch, Wizard.

## [2026-07-12] ingest | Fracture Whispers
- Source: `.raw/Fracture Whispers.md`
- Summary: [[Fracture Whispers]]
- Pages created: [[Fracture Whispers]]
- Pages updated: [[Fracture Save]] (full roll formula + 8-effect Fracture Table + narrowed contradiction), [[Whisper Points]] (dual-identity synthesis: narrative currency + instability meter, cap formula), [[Whisper Engine]] (long-standing open question largely resolved, status seed→developing), [[Sanity]] (cross-link), [[Focus]] (Fracture-drains-Focus cross-link), [[FEARS MOC]], [[index]], [[hot]]
- Key insight: The 4th and final source in this cluster with the `status: excluded`/`tags: [template]` shape — this time treated as canon by 3/3 precedent without re-asking, since the first three ([[Spell Critical]], [[Eldritch Moons in Combat]], [[Sanity & Focus in Combat]]) were each individually confirmed by the user. This is the cluster's payoff document: supplies the full Fracture Save roll (`1d20+CON+SAN`) and outcome, an 8-effect Fracture Table (closing the gap open since Spell Critical's ingest), and a Whisper Point cap formula (`1+SAN mod`, min 1). Narrows rather than resolves the DC-formula contradiction from last ingest: this source's `13+Whisper Points` now has 2-of-4 confirmed-source agreement (matching Sanity & Focus in Combat) against Spell Critical's lone `10+PB`, tipping the weight of evidence without fully explaining the discrepancy. Also resolves the multi-ingest-old Whisper Engine open question: its own Integration Hooks table states the Engine is "tied directly" to Whisper Points. Biggest editorial judgment call: synthesized (not stated outright by any single source) that Whisper Points' narrative-currency role and this source's "instability meter" role are the same resource under a push-your-luck design, based on converging textual clues rather than an explicit statement — flagged clearly as an interpretation on [[Whisper Points]] rather than presented as fact.
- Note: 1 address allocated (c-000101). `.raw/` now has **zero** remaining non-per-class FEARS files — every source outside the 24 per-class deep-dives (including `Summoner.md`) has been ingested.

## [2026-07-12] ingest | Sanity & Focus in Combat
- Source: `.raw/Sanity & Focus in Combat.md`
- Summary: [[Sanity & Focus in Combat]]
- Pages created: [[Sanity & Focus in Combat]], [[Fracture Save]]
- Pages updated: [[Sanity]] (Sanity Save formula confirmed, Fracture Save section replaced with pointer to the new contradiction page), [[Focus]] (Focus Pool / max-3 cap confirmed as a new section), [[Whisper Points]] (concrete Memory Glyph backlash award trigger), [[Momentum]] (Momentum Synergy toggle cross-link), [[FEARS MOC]], [[index]], [[hot]]
- Key insight: Third source in this cluster with the identical `status: excluded` / `tags: [template]` shape as [[Spell Critical]] and [[Eldritch Moons in Combat]] — asked the user again rather than assuming, and again confirmed as canon. Supplies the first roll formulas for both Sanity Saves (`1d20+SAN+PROF`) and a Focus Pool cap (max 3). The standout finding: this source's Fracture Save DC (`13 + Whisper Points`) directly conflicts with [[Spell Critical]]'s confirmed DC (`10 + PB`) for the same named mechanic — both sources are canon, so this is a genuine contradiction, not a drafting nuance. Spun into a dedicated [[Fracture Save]] page with a `[!contradiction]` callout rather than silently picking one, per the established contradiction-handling convention. Still unresolved even after three sources reference it: the full Fracture Effect table, and Focus's own Focus Save DC (Sanity & Focus in Combat defines Focus only as a spendable pool, not a saving throw).
- Note: 2 addresses allocated (c-000099, c-000100). `.raw/` now down to 1 non-per-class file: Fracture Whispers.md, plus 24 per-class deep-dive files including Summoner.md.

## [2026-07-11] correction + ingest | Eldritch Moons in Combat (+ Spell Critical reclassified)
- Source: `.raw/Eldritch Moons in Combat.md`
- **Correction first**: mid-ingest, the user stated "spell criticals should not be excluded." The prior ingest had filed [[Spell Critical]] (then titled "Spell Critical (Excluded Draft)") as design-history-only because its own frontmatter reads `status: excluded`, mirroring the treatment given to [[The Dynamic Combat System (Excluded Draft)]]. Per explicit user instruction, both `Spell Critical.md` and this ingest's `Eldritch Moons in Combat.md` (also `status: excluded` in its own frontmatter) are now treated as confirmed canon, **but [[The Dynamic Combat System (Excluded Draft)]] was explicitly left as-is** — a source-specific correction, not a blanket policy reversal on the `status: excluded` marker. Both pages renamed (dropped "(Excluded Draft)" from the title) and rewritten: [[Unstable Magic Zones]] now states the Spell Critical resolution table as fact instead of an unverified preview; [[Sanity]] now states the Fracture Save DC (10+PB) as confirmed while still flagging the full Fracture Effect as pending `Fracture Whispers.md`.
- Summary: [[Eldritch Moons in Combat]]
- Pages created: [[Eldritch Moons in Combat]]
- Pages updated (this ingest): [[Whisper Engine]] (new "Whisper Checks" data point, still doesn't resolve the core open question), [[Sanity]] (Eldritch Moons Sanity-pressure cross-link), [[FEARS MOC]], [[index]], [[hot]]
- Pages updated (correction): [[Spell Critical]] (renamed + rewritten as confirmed canon), [[Unstable Magic Zones]] (resolution table adopted as fact), [[Sanity]] (Fracture Save confirmed)
- Key insight: 12 named Moons, each with a combat Surge Trigger. Second confirmed sighting (after [[Spell Critical]]) of an undefined **Fracture** mechanic by name — both sources now canon, so a real Fracture subsystem is established to exist even though neither details its full rules; `Fracture Whispers.md` remains the expected resolving source. This source's `tags` field is just `template` (weaker provenance than either prior excluded-marked source), noted on its page as a caveat despite the reclassification.
- Note: 1 address allocated (c-000098). `.raw/` now down to 2 non-per-class files: Sanity & Focus in Combat, Fracture Whispers, plus 24 per-class deep-dive files including Summoner.md.

## [2026-07-11] ingest | Spell Critical
- Source: `.raw/Spell Critical.md`
- Summary: [[Spell Critical (Excluded Draft)]]
- Pages created: [[Spell Critical (Excluded Draft)]]
- Pages updated: [[Unstable Magic Zones]] (unverified-preview cross-link, no content adopted), [[Sanity]] (unverified Fracture Save/Effect cross-link), [[FEARS MOC]], [[index]], [[hot]]
- Key insight: The source's own frontmatter reads `status: excluded` — the second excluded document in this cluster after [[The Dynamic Combat System (Excluded Draft)]]. Handled identically: nothing here updates or confirms any existing page. It offers a much more structured Critical Spell Hit resolution system (six-step order, a Focus Check table determining Arcane Rift / Enhanced Arcane Rift / Wild Magic Zone / Dead Magic Zone) than [[Unstable Magic Zones]] currently documents ("no table or DC governs" — GM-adjudicated), but since it's excluded this is flagged as an unconfirmed lead, not adopted, mirroring how the Excluded Draft's Initiative preview was treated before `Initiative.md` confirmed it. Also surfaces a genuinely new undefined mechanic — Fracture Save (DC 10+PB) and Fracture Effect "from the Sanity system" — that no confirmed source names; most likely to be resolved by the still-uningested `Fracture Whispers.md`. New unconfirmed terminology (Echo Glyph, Glyphcraft, Spirit Thread resonance, leyline, Glyphburned, Circle of Echoes Druids, Moonscribes) intentionally not spun into separate stub pages per the no-thin-filler-pages convention — listed on the new page for searchability instead.
- Note: 1 address allocated (c-000097). `.raw/` now down to 3 non-per-class files: Eldritch Moons in Combat, Sanity & Focus in Combat, Fracture Whispers, plus 24 per-class deep-dive files including Summoner.md.

## [2026-07-11] ingest | Reaction-based_opportunities
- Source: `.raw/Reaction-based_opportunities.md`
- Summary: upgraded [[Tactical Reactions]] in place
- Pages created: [[Reaction Subclass Features]], [[Reaction Feats]]
- Pages updated: [[Tactical Reactions]] (Standard/Tactical category split, Reaction Economy table, DC formulas for Trap Weapon and Trip/Sweep, worked example), [[Shields]] (Great shield DR clarified: always-on +5 DR is arm-only, Block's +3 DR extension is what reaches all locations), [[Fighter]], [[Barbarian]], [[Rogue]], [[Paladin]], [[Ranger]] (each got a Reaction hook), [[FEARS MOC]], [[index]], [[hot]]
- Key insight: The eighth consecutive DCS-companion source to confirm the existing summary with zero factual drift on shared content — but the largest addition since Weapon Mastery in terms of new structural detail. Formally splits Standard Reactions from Tactical Reactions (a distinction the wiki's pages implied but never stated outright), quantifies the full Reaction Economy (including confirming, not contradicting, Momentum's existing +4-MS extra-reaction note), and surfaces the fourth independent feat-system sighting ([[Reaction Feats]]) and second subclass-system sighting ([[Reaction Subclass Features]]) — consolidated into dedicated table pages per the established no-thin-filler-pages convention, same as Called Shot's spin-offs. One genuine clarification, not a contradiction: Shields.md's Great-shield entry previously conflated the shield's always-on arm DR with Block's all-locations extension; corrected with the source's more precise wording.
- Note: 2 addresses allocated (c-000095, c-000096). `.raw/` now down to 4 non-per-class files: Spell Critical, Eldritch Moons in Combat, Sanity & Focus in Combat, Fracture Whispers, plus 24 per-class deep-dive files including Summoner.md.

## [2026-07-11] ingest | Initiative
- Source: `.raw/Initiative.md`
- Summary: [[Initiative System]]
- Pages created: [[Initiative System]], [[Initiative]], [[Seize the Moment]]
- Pages updated: [[The Dynamic Combat System (Excluded Draft)]] (Initiative preview upgraded from "unverified" to "confirmed accurate"), [[Paladin]], [[Bard]], [[Investigator]], [[Warlock]], [[Ranger]], [[Druid]], [[Fighter]], [[Barbarian]], [[Rogue]], [[Monk]] (each got a class-specific Seize the Moment hook), [[FEARS MOC]], [[index]], [[hot]]
- Key insight: The first piece of [[The Dynamic Combat System (Excluded Draft)]] independently verified rather than superseded — its two-phase Initiative preview (traditional round 1, Momentum-average-driven Side Initiative from round 2) survived unchanged into this canonical source. The genuinely new content is [[Seize the Moment]], a Focus-based PC reaction with no precedent in any prior source (including the excluded draft), which competes directly with several classes' existing reaction economy (Uncanny Dodge, Deflect Missiles, Patient Defense) rather than being a free bonus. Did not resolve the still-open Called Shot save-DC formula question.
- Note: 3 addresses allocated (c-000092 through c-000094). `.raw/` now down to 6 non-per-class files: Reaction-based Opportunities, Spell Critical, Eldritch Moons in Combat, Sanity & Focus in Combat, Fracture Whispers, plus 24 per-class deep-dive files including Summoner.md.

## [2026-07-11] ingest | Weapon Mastery System
- Source: `.raw/Weapon Mastery System.md`
- Summary: [[Weapon Mastery System]]
- Pages created: [[Weapon Mastery System]], [[Weapon Mastery]], [[Weapon Skills]], [[Weapon Mastery Feats]]
- Pages updated: [[Monk]] (Focus/Technique-Point conflict resolved — 3rd confirming source), [[Bender]] (newly discovered to share Monk's Technique Point mechanic entirely), [[Fighter]] (exact multi-mastery math: 1 Attack + 1 BA + 1 Reaction + 1 Action Surge = 2-4 skills/round), [[Binder]] (flagged the Summoner/Binder version mismatch), [[FEARS MOC]], [[index]], [[hot]]
- Key insight: The largest single document in the cluster (~850 lines) — the martial-class engine every prior combat source referenced without ever defining ("Weapon Mastery Skill" interactions mentioned in Called Shot/Combat Flow/Momentum since early ingests). Resolved the Focus-vs-Technique-Point naming question definitively (three independent deeper sources now agree). Revealed a genuinely new cross-class connection: Bender shares Monk's exact Flow Strike/Technique Point resource, never stated anywhere else. Also surfaced a second version-mismatch artifact (after the Excluded Draft): this document still treats "Summoner" as the current class name throughout and never mentions "Binder" once, despite Classes_Summary confirming the replacement — not marked excluded like the DCS draft, so flagged as a likely-stale snapshot rather than dismissed outright. Deliberately kept per-class weapon *recommendations* (flavor content) inside the source/hub pages rather than pushing them into all 24 individual class pages — would have been enormous scope creep for information that's more flavor than mechanical crunch.
- Note: 4 addresses allocated (c-000088 through c-000091). `.raw/` now down to 7 non-per-class files: Initiative, Reaction-based Opportunities, Spell Critical, Eldritch Moons in Combat, Sanity & Focus in Combat, Fracture Whispers, plus 24 per-class deep-dive files including Summoner.md.

## [2026-07-11] ingest | The Dynamic Combat System
- Source: `.raw/The Dynamic Combat System.md`
- Summary: [[The Dynamic Combat System (Excluded Draft)]]
- Pages created: [[The Dynamic Combat System (Excluded Draft)]]
- Pages updated: [[Momentum]] (design-history note on the cut −3 tier), [[Called Shot]] (design-history note on the unconfirmed save-DC formula), [[FEARS MOC]], [[index]], [[hot]]
- Key insight: This resolves the "relationship to DCS.md not yet checked" question every prior ingest since `Class_breakdown` had flagged. Answer: it's "Version 2.0," an earlier draft the source material's own frontmatter marks `status: excluded` — explicitly removed from canon, not a companion document. Handled completely differently from the last seven DCS-companion sources: nothing in it was used to update confirmed numbers. Instead it's documented as design history (Momentum's range was −3 to +3 with an "Overwhelmed" tier before being cut to −2 to +3; several class-specific Momentum rules were reworked) and as an unverified preview of ground no confirmed source has reached yet (a full Initiative system, monster-conversion-by-size tables, DM implementation guidance). It also happens to answer a real open gap — a Called Shot save DC formula (`8 + PB + ability mod`) that no confirmed source states — but since the source is excluded, that answer is flagged as unconfirmed, not adopted.
- Note: 1 address allocated (c-000087). `.raw/` still holds: `Weapon Mastery System.md`, `Initiative.md`, `Reaction-based_opportunities.md`, `Spell Critical.md`, `Eldritch Moons in Combat.md`, `Sanity & Focus in Combat.md`, `Fracture Whispers.md`, plus 24 per-class deep-dive files.

## [2026-07-11] ingest | Injury System
- Source: `.raw/Injury System.md`
- Summary: [[Injury System]] (upgraded in place)
- Pages created: none — same in-place-upgrade pattern as the last five DCS-companion ingests
- Pages updated: [[Injury System]] (confirmed DCS's numbers with zero drift; added full 24-injury tables across Minor/Major/Critical tiers, a healing-methods table, and 8 monster-type injury variants; **corrected** this page's own prior framing that implied the system was PC-only — it applies to all creatures, monsters use it in addition to Bloodied, not instead of it), [[Paladin]] (Sanctified Intercession hook added), [[FEARS MOC]], [[index]], [[hot]]
- Key insight: Seventh consecutive DCS-companion source to confirm with zero factual drift — but this is the first one where the correction wasn't just "more detail," it was a genuine scope error in the wiki's own prior summary (implying PC-only when the system is universal). Worth remembering going forward: "DCS-level summary, provisional" pages in this cluster can undersell scope, not just omit numbers — a reason to keep checking the remaining ones rather than assuming they're merely thin.
- Note: no DragonScale address allocated — reused c-000079 (Injury System's existing address). `.raw/` still holds the same batch of files, minus Injury System.md. Four DCS-adjacent files remain uningested: Weapon Mastery System, Initiative, Reaction-based Opportunities, and the unexplained second `The Dynamic Combat System.md`.

## [2026-07-11] ingest | Evasion
- Source: `.raw/Evasion.md`
- Summary: [[Evasion]] (upgraded in place)
- Pages created: [[Evasion Feats]]
- Pages updated: [[Evasion]] (confirmed DCS's numbers with zero drift; added monster-Evasion table, class-hooks confirmation, feat-system cross-reference), [[Monk]] (flagged a Focus-vs-Technique-Point terminology conflict rather than silently resolving it; added teleport-counterattack detail), [[FEARS MOC]], [[index]], [[hot]]
- Key insight: Sixth consecutive DCS-companion source to confirm with zero factual drift on shared content. Second independent feat-system sighting (after Called Shots.md) — 4 Evasion-specific feats, completely disjoint from the 14 Called-Shot feats, which is good evidence this is a real broad feat system rather than a single-mechanic gimmick invented once. Also surfaced a genuine small terminology conflict: two deeper sources (this one and Damage Reduction.md) call Monk's reroll resource "Technique Point," while the original DCS.md summary called it "Focus" — flagged on Monk's page rather than assuming which is correct.
- Note: 1 address allocated (c-000086) for [[Evasion Feats]]; Evasion's own page reused its existing address (c-000073). `.raw/` still holds the same batch of files, minus Evasion.md.

## [2026-07-11] ingest | Momentum
- Source: `.raw/Momentum.md`
- Summary: [[Momentum]] (upgraded in place)
- Pages created: none — same in-place-upgrade pattern as Combat Flow, Called Shot, Damage Reduction
- Pages updated: [[Momentum]] (confirmed DCS's numbers with zero drift; added monster-scaling table by creature type, epic-tier PC and monster effects tables, Barbarian's level-7 Primal Defiance, caster Spell Save DC floor, Exhaustion interaction, threshold-crossing clarification), [[Barbarian]] (level-7 ability added to existing Rage progression), [[FEARS MOC]], [[index]], [[hot]]
- Key insight: Fifth consecutive DCS-companion source to confirm with zero factual drift. Unlike the last two (Called Shots, Damage Reduction), this one didn't reveal any third unrelated system — all its new content (monster scaling, epic tiers, caster DC floor) stayed within Momentum's own scope. Worth noting as the pattern isn't "every deeper source reveals something new," just "every deeper source confirms the summary."
- Note: no DragonScale address allocated — reused c-000077 (Momentum's existing address). `.raw/` still holds the same large batch of files, minus Momentum.md.

## [2026-07-11] ingest | Damage Reduction
- Source: `.raw/Damage Reduction.md`
- Summary: [[Damage Reduction]] (upgraded in place)
- Pages created: none — same in-place-upgrade pattern as Combat Flow and Called Shot (filename/subject collision with the existing DCS-summary page)
- Pages updated: [[Damage Reduction]] (confirmed DCS's numbers with zero drift; added a Magical and Natural DR table, class DR formulas, DR-reduction-stacking floor rule), [[Barbarian]], [[Monk]], [[Fighter]], [[Ranger]] (new specific DR formulas added to existing hooks), [[Druid]] (first DCS class hook of any kind — Circle of the Moon Wild Shape DR), [[FEARS MOC]], [[index]], [[hot]]
- Key insight: Fourth consecutive DCS-companion source confirmed with zero factual drift, extending the pattern from Combat Flow/Bloodied Breaking Points Rally/Called Shot. Also the second source in a row (after Called Shots.md) to reveal something DCS's original summary gave no hint of: a "Magical and Natural DR" layer including FEARS's first-ever race mention (Dragonborn, one line, no further detail) and a "Tough" feat with no Called Shot tie — confirming the feat system discovered last ingest extends beyond just Called Shot interactions.
- Note: no DragonScale address allocated — reused c-000074 (Damage Reduction's existing address). `.raw/` still holds the same large batch of files, minus Damage Reduction.md.

## [2026-07-11] ingest | Called Shots
- Source: `.raw/Called Shots.md`
- Summary: [[Called Shot]] (upgraded in place)
- Pages created: [[Called Shot Subclass Features]], [[Called Shot Feats]]
- Pages updated: [[Called Shot]] (Momentum/Injury integration, DR-bypass worked table, confidence low→high), [[Rogue]], [[Monk]], [[Fighter]], [[Barbarian]], [[Ranger]], [[Paladin]], [[Bard]], [[Warlock]], [[Wizard]] (Called Shot subclass cross-links), [[FEARS MOC]], [[index]], [[hot]]
- Key insight: Third consecutive deeper-source check (after Combat Flow, Bloodied Breaking Points Rally) that confirmed the DCS summary with zero factual drift — but this one also surfaced two entirely new systems DCS's summary gave no hint of: a subclass layer and a feat layer, both known only through their narrow Called Shot interaction. Deliberately did not create per-subclass or per-feat pages (11 subclasses, 14 feats) since there's no other content to put on them yet — consolidated into two table pages instead, flagged clearly as a narrow window into a larger unconfirmed system rather than a full reference.
- Note: no separate source page created (same pattern as Combat Flow — this deepens the existing [[Called Shot]] page directly). 2 addresses allocated (c-000084, c-000085) for the two genuinely new pages. `.raw/` still holds the same large batch of files, minus Called Shots.md.

## [2026-07-11] ingest | Combat Flow
- Source: `.raw/Combat Flow.md`
- Summary: [[Combat Flow]] (upgraded in place)
- Pages created: none — filename collided with the existing [[Combat Flow]] concept page (already a DCS-level summary of exactly this subsystem), so the existing page was upgraded rather than duplicated
- Pages updated: [[Combat Flow]] (9-step DCS summary → full 12-step sequence, Q&A, worked example, confidence low→high), [[Tactical Reactions]] (corrected: "Trap / Disarm" was actually two distinct reactions, not one combined row), [[Dynamic Combat System (DCS)]] (updated its own uningested-files list and step count), [[FEARS MOC]]
- Key insight: This is the first deeper DCS-companion source checked against its summary, and it confirmed DCS's summary with **zero factual drift** — every formula matched exactly, the only change was more granularity plus one real correction (Trap Weapon vs. Disarm being separate reactions). This is a good signal for the reliability of the other still-uningested DCS-summary pages (Momentum, Injury System, Called Shots, Evasion, Damage Reduction) — noted on the MOC as a pattern to watch, not assumed to hold for all of them.
- Note: no DragonScale address allocated — reused c-000078 (existing Combat Flow address) since no new page was created, per the idempotency rule (reuse an existing page's address rather than allocating a new one). `.raw/` still holds the same large batch of files flagged two ingests ago, minus Combat Flow.md.

## [2026-07-11] ingest | Bloodied Breaking Points Rally
- Source: `.raw/Bloodied Breaking Points Rally.md`
- Summary: [[Bloodied Breaking Points Rally]]
- Pages created: [[Bloodied Breaking Points Rally]], [[Bloodied and Bruised]], [[Breaking Points]], [[Enemy Rally]]
- Pages updated: [[Combat Flow]], [[Momentum]], [[Injury System]], [[Called Shot]] (cross-linked to the new enemy-morale pages), [[Bard]], [[Warlock]], [[Cleric]] (new enemy-morale Class Hooks), [[Paladin]], [[Investigator]] (added enemy-morale hooks alongside their existing DCS hooks), [[FEARS MOC]], [[index]], [[hot]]
- Key insight: This source confirmed and fully elaborated a single sentence [[Combat Flow]] already carried ("Bloodied... monsters only, not player characters") — clean cross-reference, zero contradiction. It's explicitly asymmetric by design (PCs use only the Injury System) with a clearly-labeled, off-by-default optional variant for tables that want PC morale checks too — noted but not adopted as the assumed ruleset. Surfaced one soft tension worth tracking: Cleric's Turn Undead forces an "automatic rout" on undead, but [[Breaking Points]] states undead/constructs are flatly immune to morale — read as a specific spell-granted exception rather than a contradiction, flagged as an open question rather than silently resolved either way.
- Note: same manual DragonScale address allocation (`flock` unavailable); addresses c-000080 through c-000083 assigned. `.raw/` still holds a large batch of uningested FEARS files from two ingests ago — this pass only touched the requested file.

## [2026-07-11] ingest | DCS
- Source: `.raw/DCS.md`
- Summary: [[Dynamic Combat System (DCS)]]
- Pages created: [[Dynamic Combat System (DCS)]], [[Evasion]], [[Damage Reduction]], [[Shields]], [[Tactical Reactions]], [[Momentum]], [[Combat Flow]], [[Injury System]]
- Pages updated: [[Called Shot]] (stub → full penalty/save/detection tables), [[FEARS Combat System]] (repositioned as narrative-level entry point, links forward to DCS), [[Rogue]], [[Monk]], [[Ranger]], [[Barbarian]], [[Paladin]], [[Fighter]], [[Magus]], [[Investigator]], [[Shaman]], [[Witch]] (DCS Class Hooks added), [[FEARS MOC]], [[index]], [[hot]]
- Key insight: This source resolved nearly every "not specified" caveat the MOC had been carrying since the very first ingest — real Evasion/Damage Reduction/Called Shot/Momentum formulas, all previously described only narratively. It also explicitly self-identifies as a hub/summary document deferring to deeper source files for Momentum and the Injury System specifically — every combat subsystem page created this ingest is marked "DCS-level summary, provisional" rather than presented as final.
- **Major finding mid-ingest**: a large new batch of FEARS files appeared in `.raw/` alongside the requested `DCS.md` — full per-class deep-dive documents for all 24 classes (including `Summoner.md`, the retired class), and ~14 more combat/mechanics files (`Momentum.md`, `Injury System.md`, `Called Shots.md`, `Combat Flow.md`, `Evasion.md`, `Damage Reduction.md`, `Weapon Mastery System.md`, `Initiative.md`, `Reaction-based_opportunities.md`, a second file `The Dynamic Combat System.md` whose relationship to `DCS.md` is unchecked, `Spell Critical.md`, `Eldritch Moons in Combat.md`, `Sanity & Focus in Combat.md`, `Bloodied Breaking Points Rally.md`, `Fracture Whispers.md`). None of these were ingested this pass — only `DCS.md` as explicitly requested. Corrected the MOC's previous "7/7 fully ingested" claim, which was accurate only until this batch landed.
- Note: same manual DragonScale address allocation (`flock` unavailable); addresses c-000072 through c-000079 assigned.

## [2026-07-11] ingest | Class_breakdown
- Source: `.raw/Class_breakdown.md`
- Summary: [[Class_breakdown]]
- Pages created: [[Class_breakdown]], [[FEARS Class Format]], [[Barbarian]], [[Fighter]], [[Monk]], [[Rogue]], [[Ranger]], [[Paladin]], [[Wizard]], [[Sorcerer]], [[Warlock]], [[Druid]], [[Cleric]], [[Bard]]
- Pages updated: [[Investigator]], [[Inventor]], [[Apothecary]], [[Magus]], [[Sangromancer]], [[Shaman]], [[Tattooist]], [[Witch]], [[Bender]], [[Warden]], [[Reaper]], [[Binder]], [[FEARS Class Roster]], [[FEARS MOC]], [[index]], [[hot]]
- Key insight: This source's depth reversed an earlier editorial call — the 12 "Core" 5E-derived classes were deliberately left without dedicated pages during the [[Classes_Summary]] ingest for having "zero FEARS-specific content beyond being named." This source proved that wrong: every one of them gets a distinct FEARS-flavored identity (Fighter's "Action Surge: Break the action economy," Cleric's "prevents failure — stopping collapse before it happens"), so all 12 now have pages. Also surfaced a real naming collision rather than smoothing it over: "Exploit Weakness" was Investigator's signature ability per [[Welcome to FEARS]], but this source gives that exact name to Rogue and renames Investigator's to "Exploit Vulnerability" — flagged on both pages as unresolved, not assumed to be a rename or an error. Several other classes show similar thematically-consistent-but-differently-named abilities across sources (Sangromancer, Shaman) — noted as a recurring pattern, not individually flagged as contradictions each time.
- Note: same manual DragonScale address allocation (`flock` unavailable); addresses c-000058 through c-000071 assigned (14 addresses for 14 new pages). This closes out all 7 known FEARS-adjacent files in `.raw/` — nothing left pending for this cluster as of this ingest.

## [2026-07-11] ingest | Classes_Summary
- Source: `.raw/Classes_Summary.md`
- Summary: [[Classes_Summary]]
- Pages created: [[Classes_Summary]], [[FEARS Class Roster]], [[Binder]]
- Pages updated (contradiction — marked `retired` with `[!contradiction]` callouts, not deleted): [[Psion]], [[Runesmith]], [[Shadowbinder]], [[Tamer]], [[Thaumaturge]]
- Pages updated (class data added — caster tier, resource, hit die): [[Investigator]], [[Inventor]], [[Magus]], [[Sangromancer]], [[Shaman]], [[Tattooist]], [[Witch]], [[Bender]], [[Warden]], [[Reaper]], [[Apothecary]]
- Pages updated (structural): [[FEARS MOC]] (archetype section rebuilt around the 24-class roster, several open questions resolved), [[index]], [[hot]]
- Key insight: This is the first source in the cluster that explicitly self-identifies as a correction of prior (incomplete) content, and it directly contradicts this wiki's very first ingest — 5 of the original 12 archetypes from [[Welcome to FEARS]] (Psion, Runesmith, Shadowbinder, Tamer, Thaumaturge) are now "retired, should not appear in new content." Followed the vault's established contradiction convention exactly: flagged with `[!contradiction]` callouts and `status: retired`, content preserved as historical record, nothing deleted. Also resolved two previously-open MOC questions in one pass (exact class count = 24; why 6 of the original 12 got no mention in Narrative Identity = they'd already been cut) and surfaced a new one (this source reveals the real FEARS design material lives in an external vault this wiki only gets periodic snapshots of — explains the recurring contradictions across ingests).
- Note: same manual DragonScale address allocation (`flock` unavailable); addresses c-000055 through c-000057 assigned (only 3 new pages — most of this ingest's volume was corrective updates to 16 existing pages). `.raw/` still has one more FEARS file not yet requested: `Class_breakdown.md` (17KB).

## [2026-07-11] ingest | Narrative Identity
- Source: `.raw/Narrative Identity.md`
- Summary: [[Narrative Identity]]
- Pages created: [[Narrative Identity]], [[Narrative Identity Framework]], [[Warden]], [[Reaper]], [[Bender]], [[Apothecary]], [[Spirit Debt]], [[Territory Bond]]
- Pages updated: [[Witch]] (full narrative-identity worked example added), [[FEARS MOC]] (restructured Archetypes section into original-12 vs. new-from-this-source vs. no-page-thin-content tiers, added class-roster-discrepancy and archetype-coverage-gap open questions), [[index]], [[hot]]
- Key insight: This source is categorically different from the other four — no frontmatter, no in-fiction narrator, reads as a direct design consultation ending in "if you want, next I can turn this into a worksheet." Filed with `confidence: low` and an explicit status note on every derived page so its class/currency proposals aren't mistaken for the same tier of confirmed canon as the rulebook-style sources. Revealed FEARS has far more than 12 archetypes (4 new + ~11 standard 5E imports), and that 6 of the original 12 archetypes get zero mention here — a real gap, not silently smoothed over. Deliberately did NOT create pages for 5 undefined proposed currencies (Obsession, Death Resonance, Elemental Imbalance, Invention Heat, Blood Taint) or the 11 standard 5E classes, since they have no FEARS-specific content beyond being named — editorial judgment per the no-thin-filler-pages precedent set in earlier ingests.
- Note: same manual DragonScale address allocation (`flock` unavailable); addresses c-000047 through c-000054 assigned. This closes out all 5 FEARS-adjacent sources originally found in `.raw/` — no more known files pending for this cluster.

## [2026-07-11] ingest | Four Threads of the Mind
- Source: `.raw/Four Threads of the Mind.md`
- Summary: [[Four Threads of the Mind]]
- Pages created: [[Four Threads of the Mind]], [[Archivists of the Shattered Loom]], [[The Weave]], [[Burned out]], [[Broken]]
- Pages updated: [[Focus]] (Focus Save, Burned out, confirmed Corruption cascade), [[Sanity]] (Sanity Save, Broken, confirmed Focus cascade), [[Corruption]] (numeric thresholds 5/10/15/20, Weave connection), [[Luck]] (reframed via The Weave), [[Mental State]] (partial-resolution note, not a confirmed merge), [[FEARS MOC]] (new Setting/People entries, several open questions closed or added), [[index]], [[hot]]
- Key insight: First source marked `status: complete` rather than wip/revision-needed — elevated as the tiebreaker source if future ingests conflict with it. Surfaced a genuine ambiguity rather than resolving it by fiat: this source's "Broken" (0 Sanity) may or may not be the same state as [[Mental State]]'s terminal "Broken" stage from the previous ingest — both pages now cross-link the open question instead of one silently absorbing the other. Also named [[The Weave]], the cosmological force three earlier sources had referenced only obliquely without naming it.
- Note: same manual DragonScale address allocation (`flock` unavailable); addresses c-000042 through c-000046 assigned. Caught and fixed one link-integrity bug before finishing: a `[[Short Rest]]` link inside backticks in my own synthesis still resolved as a real wikilink in Obsidian (backticks don't escape wikilinks) — reworded to avoid it rather than create a thin filler page for a generic 5E term. `.raw/` has one FEARS source left: `Narrative Identity.md` (15KB, largest remaining file).

## [2026-07-11] ingest | FEARS Character Framework
- Source: `.raw/FEARS Character Framework.md`
- Summary: [[FEARS Character Framework]]
- Pages created: [[FEARS Character Framework]], [[FEARS Character Sheet]], [[Mental State]], [[Called Shot]]
- Pages updated: [[FEARS Combat System]] (Evasion formula `1d20+DEX+PROF`, per-body-part DR, Reactions detail), [[Whisper Points]] (starting-pool formula `3+Focus Mod+½Sanity Mod`), [[Translation Matrix]] (partial concrete conversion steps), [[Sanity]] (SAN abbreviation, Mental State link), [[Focus]] (FOC abbreviation, Mental State link), [[Corruption]] (Corruption Score/CS formalized, Mental State link), [[FEARS MOC]] (new Character Sheet & Crunch section, several open questions marked partially resolved), [[index]], [[hot]]
- Key insight: This source supplied the numeric crunch the MOC had been flagging as entirely missing since the first ingest — did NOT create duplicate "Evasions"/"Damage Reductions" pages despite the source's own (typo'd) wikilink text suggesting separate pages, since that content belongs inside the existing [[FEARS Combat System]] page. Editorial judgment applied per the no-duplicate-pages rule.
- Note: same manual DragonScale address allocation as prior FEARS ingests (`flock` unavailable); addresses c-000038 through c-000041 assigned (only 4 new pages this time — most of the value was updates to existing pages, not new ones). `.raw/` still holds 2 more uningested FEARS-adjacent sources (`Four Threads of the Mind.md`, `Narrative Identity.md`).

## [2026-07-11] ingest | A World that Watches
- Source: `.raw/A World that Watches.md`
- Summary: [[A World that Watches]]
- Pages created: [[A World that Watches]], [[Dór-o Estel]], [[Disposition]], [[Wanted Score]], [[Reputation]], [[Black Market]], [[Hideouts]], [[Sanity]], [[Focus]], [[Corruption]], [[Luck]], [[Memory]], [[Occult]], [[Streetwise]], [[Whisper Engine]]
- Pages updated: [[Translation Matrix]] (linked forward to Sanity/Focus/Streetwise, its own undefined mentions of them), [[Dynamic Action Economy]] (linked forward to Whisper Engine), [[FEARS MOC]] (added Setting + Social & mental systems sections, new open questions), [[index]], [[hot]]
- Key insight: This source retroactively resolved three dangling references from the first FEARS ingest — Focus, Sanity, and Streetwise were named but undefined in [[Translation Matrix]]; this doc is their first real definition, filed as a gap-fill rather than a contradiction. One genuine open thread remains: Whisper Engine (mentioned in both sources) still isn't defined by either — flagged on [[FEARS MOC]] and on the new [[Whisper Engine]] stub page.
- Note: same manual DragonScale address allocation as the previous FEARS ingest (`flock` unavailable); addresses c-000023 through c-000037 assigned. `.raw/` still holds 3 more uningested FEARS-adjacent sources (`FEARS Character Framework.md`, `Four Threads of the Mind.md`, `Narrative Identity.md`), noted on [[FEARS MOC]] as likely where archetype crunch and Mental Triad resolution mechanics live.

## [2026-07-11] ingest | Welcome to FEARS
- Source: `.raw/Welcome to FEARS.md`
- Summary: [[Welcome to FEARS]]
- Pages created: [[Welcome to FEARS]], [[FEARS MOC]], [[FEARS Combat System]], [[Whisper Points]], [[Dynamic Action Economy]], [[Unstable Magic Zones]], [[Translation Matrix]], [[Consequence Engine]], [[Daldir Lunadreamer]], [[Investigator]], [[Inventor]], [[Magus]], [[Psion]], [[Runesmith]], [[Sangromancer]], [[Shadowbinder]], [[Shaman]], [[Tamer]], [[Tattooist]], [[Thaumaturge]], [[Witch]]
- Pages updated: [[index]], [[hot]]
- Key insight: First source in an entirely new domain (TTRPG system, not claude-obsidian ecosystem content) — full granularity chosen by user, 12 archetype pages created despite each having only a one-line mechanical description in the source. Source itself is marked `status: revision-needed`; Translation Matrix (the 5E-compatibility claim) is the least-detailed and highest-risk-of-contradiction concept if a mechanics follow-up source is ingested later.
- Note: DragonScale addresses c-000003 through c-000022 assigned via manual counter increment (`flock` unavailable in this Git Bash environment; `scripts/allocate-address.sh` and `scripts/wiki-lock.sh` both depend on it and could not run). Single-writer session, no lock contention risk.

## [2026-04-24] save | v1.6.0 public release notes (Teams, Karpathy-style)
- Type: release doc + visual assets
- Locations (new): `docs/releases/v1.6.0.md` (346 lines, 6 sections, Karpathy-style prose), `wiki/meta/dragonscale-mechanism-overview.svg` (4-mechanism diagram with shared .vault-meta/ gate), `wiki/meta/dragonscale-6-test-flow.svg` (validation timeline), `wiki/meta/dragonscale-frontier-graph.svg` (M4 candidate + 3 filed pages)
- Locations (modified): `wiki/meta/2026-04-24-v1.6.0-release-session.md` (cross-reference added pointing to public release notes)
- Scope: Teams approach. R1 (chair) wrote 3 original SVGs per SVG Diagram Style Guide. R2 (codex worker) drafted Karpathy-style release prose. R3 (chair) stitched SVGs, pivoted Wikipedia imagery to text links only (no binary vendoring per permission). R4 (codex verifier) returned ACCEPT WITH FIXES, 3 wording fixes on version narrative. R5 (chair) applied fixes, committed.
- Style: direct, short, signal-dense, lists over prose, no em dashes, no marketing terms. Verifier confirmed zero em-dashes and zero banned marketing language ('revolutionary', 'seamless', 'world-class', 'game-changing', 'unlock', 'transform').
- Distribution (all three destinations covered): (1) `docs/releases/v1.6.0.md` public-facing file (commit `85515bb`), (2) `wiki/meta/2026-04-24-v1.6.0-release-session.md` internal engineering record (cross-linked), (3) GitHub Release body (user to paste from docs/releases/v1.6.0.md when ready to `gh release create v1.6.0`).
- Wikipedia imagery: referenced as text link to `https://en.wikipedia.org/wiki/Dragon_curve` rather than hotlinked or vendored. Cleaner license-wise (no CC-BY-SA attribution needed) and no external dependency. The 3 original SVGs carry the visual load instead.
- PII scan post-write: `docs/releases/v1.6.0.md` + all three SVGs are clean. No `/home/` paths, no real emails, no tokens.
- Next recommended: user runs `gh release create v1.6.0 --notes-file docs/releases/v1.6.0.md` when ready to cut the public release. This also creates the annotated tag.

## [2026-04-24] save | DragonScale end-to-end validation pass (Teams, 6 tests)
- Type: validation + first real fold + first real autoresearch
- Tests executed (all green):
  - T0 ollama pull `nomic-embed-text`: done (274MB, 15s wall)
  - T1 M1 dry-run k=3 via codex: DRY-RUN OK, 8 children, no em-dashes
  - T2 M2 real allocate: counter advanced 2 to 3, got `c-000002` (unassigned reservation; gap acceptable per spec)
  - T3 M3 full tiling with model present: 41 pages scanned, 21 embedded, 20 correctly skipped (meta/excluded/embed-error), 0 errors at >=0.9, 15 pairs in 0.8-0.9 review band (top 0.8822 Compounding Knowledge vs LLM Wiki Pattern, a legitimate semantic neighbor), report at `wiki/meta/tiling-report-2026-04-24.md`
  - T4 M1 commit via codex: first real fold committed, `wiki/folds/fold-k3-from-2026-04-23-to-2026-04-24-n8.md` (115 lines, 8 children, flat extractive). Flips the long-standing "no fold committed yet" status
  - T6 M4 autoresearch no-topic via codex: selected "How does the LLM Wiki pattern work?" as candidate (score 1.7022, #3 after skipping top-1 source + top-2 self-reference); 6 web fetches (Karpathy gist, RAG paper arXiv 2005.11401, MemGPT arXiv 2310.08560, Obsidian docs); 3 new concept pages filed, each with Primary Sources
- Locations (new): `wiki/folds/fold-k3-from-2026-04-23-to-2026-04-24-n8.md`, `wiki/meta/tiling-report-2026-04-24.md`, `wiki/concepts/Persistent Wiki Artifact.md`, `wiki/concepts/Source-First Synthesis.md`, `wiki/concepts/Query-Time Retrieval.md`
- Locations (modified): `.vault-meta/address-counter.txt` (2 to 3), `wiki/index.md` (3 concept links), `wiki/concepts/_index.md` (3 concept links)
- Scope: six-test menu the user approved. Codex gpt-5.4 for T1/T4/T6 (sub-agent delegation); chair for T0/T2/T3 (one-shot shell) and all integration (index, log, hot, commit).
- Style: all new content uses colons or parens instead of em-dashes. Pre-existing em-dashes in index entries and wiki/concepts/_index.md left as-is (clean-room boundary; deferred to F-slice style pass).
- Tests still green: `make test` passes (74+ assertions).
- Integration: chair added the 3 new concepts to `wiki/index.md` and `wiki/concepts/_index.md` with colon-style descriptions so the fresh pages are discoverable. The cluster extends `[[How does the LLM Wiki pattern work?]]` and cross-references `[[LLM Wiki Pattern]]`.
- Next recommended slice: either (G) commit this test batch and declare v1.6.0 validated, or (H) run a second fold k=3 now that 8 newer entries exist above this one and close the hierarchical-fold-not-yet-supported loop in a future phase.

## [2026-04-24] save | v1.6.0 closeout (Teams, chair-led)
- Type: docs + release hygiene
- Locations (new): wiki/meta/2026-04-24-v1.6.0-release-session.md (release session summary, 346 lines), wiki/meta/boundary-frontier-2026-04-24.md (first M4 run artifact against this vault), docs/dragonscale-guide.md (user-facing DragonScale guide, 563 lines)
- Locations (modified): wiki/hot.md (tag-claim fix, Scripts line adds boundary-score, tests line adds test_boundary_score, push-line drift, tiling line-count, one em-dash), docs/install-guide.md (version 1.5.0 to 1.6.0, DragonScale callout expanded to all four mechanisms, "hierarchical log folds" corrected to "flat extractive log folds", points to docs/dragonscale-guide.md), README.md (DragonScale parenthetical expanded to all four mechanisms plus guide link)
- Scope: Teams approach, chair-led. Slice A (2 codex read-only explorers: closeout punch list + doc-surface map). Slice B (6 bounded writes: 4 chair, 2 codex workers, non-overlapping write scopes). Slice C (codex adversarial verifier, ACCEPT WITH FIXES). Slice D (fix pass + log entry + manual commit of docs + README).
- Verifier: C1 found 11 items across 6 files. All 11 applied. Flag typos `--allow-remote-ollama` and `--report PATH` corrected in release-session; boundary-frontier provenance corrected to `--top 7` to match default vs explicit top; hot.md tiling line-count claim stripped to avoid drift; hot.md "local tag only" corrected to "local commits only, no git tag"; install-guide log-fold wording corrected from "hierarchical" to "flat extractive"; dragonscale-guide rollback wording corrected (`.vault-meta/` is a shared gate across M2+M3+M4, not per-mechanism).
- Model: codex gpt-5.4 used throughout. User requested gpt-5.5; not reachable via codex CLI 0.123.0 / this account at the time. models_cache lists max gpt-5.4, and the API rejects gpt-5.5 with "does not exist or you do not have access". Existing config already has `service_tier = "fast"` and `sandbox_mode = "workspace-write"`, matching the "fast for chatgpt with permission of full access" intent.
- Tests: `make test` passes. test_allocate_address.sh (shell, 12 assertions), test_tiling_check.py (python, 18 assertions), test_boundary_score.py (python, 44 assertions). Zero ollama dependency.
- Tags: still no local v1.5.0 / v1.5.1 / v1.6.0 tags. User controls tag creation and push. Pre-existing tags unchanged (v1.1, v1.4.0 through v1.4.3).
- Deliberately NOT done: no real M1 fold committed; no M3 end-to-end run (needs `ollama pull nomic-embed-text`); pre-existing em-dashes in install-guide.md and README.md left untouched (clean-room boundary, not in write scope this slice); CLAUDE.md pre-existing uncommitted change left untouched.
- Next recommended slice: either (E) push to origin/main and create annotated tags v1.5.0, v1.5.1, v1.6.0 in landing order, or (F) dedicated style pass to scrub pre-existing em-dashes across install-guide.md, README.md, and any other wiki files flagged by a grep scan.

## [2026-04-24] save | DragonScale Phase 4 — boundary-first autoresearch shipped (v1.6.0)
- Type: feature release
- Locations (new): scripts/boundary-score.py (with --top, --page, --json, stdout-only CLI), tests/test_boundary_score.py (40+ assertions)
- Locations (modified): skills/autoresearch/SKILL.md (new Topic Selection section A/B/C with helper-failure fallback), commands/autoresearch.md (no-topic candidate flow with agenda-control label), wiki/concepts/DragonScale Memory.md (v0.4: M4 flipped from NOT IMPLEMENTED to shipped; exact formula without recency floor; filename-stem disclosure; fence-handling qualifiers), CHANGELOG.md, .claude-plugin/{plugin,marketplace}.json (1.5.0 -> 1.6.0), Makefile (test-boundary target), wiki/hot.md, wiki/index.md, wiki/concepts/_index.md (status drift resolved).
- Scope: boundary-first autoresearch as opt-in Topic Selection mode. `/autoresearch` without a topic surfaces top-5 frontier pages; user picks/overrides/declines. Explicit helper-failure fallback to user-ask. Labeled "agenda control" throughout to match the spec's scope disclosure.
- Correctness: filename-stem resolution including folder-qualified `[[notes/Foo]]` -> Foo.md. Self-loops, unresolved targets, meta-targets, symlinks, and vault escapes all excluded. Code-fence parser handles backticks AND tildes with CommonMark length tracking (longer opening fence is not closed by shorter inner fence). Indented blocks intentionally not filtered (Obsidian bullet convention).
- Recency: exp(-days/30), no floor. Stale pages approach zero weight so they do not dominate frontier ranking.
- Review rounds: codex adversarial Phase 4 round 1 (10 items: 7 reject + 3 refine). Round 2 (7 accept + 3 still-reject: folder-qualified stem, docstring floor mention, hot.md historical drift). Round 3 (3 accept, PASS).
- Phase 3.6 (pre-Phase-4 hardening) already landed as v1.5.1: tiling --report VAULT_ROOT confinement, rollout baseline, AGENTS.md consistency, wiki-ingest .raw/ contradiction, install-guide version.
- All four DragonScale mechanisms now shipped and opt-in. 44 commits ahead of origin/main, no push.

## [2026-04-24] save | DragonScale Phase 3.5 — cross-phase hardening to v1.5.0
- Type: release hardening
- Locations (new): bin/setup-dragonscale.sh (opt-in installer), tests/test_allocate_address.sh, tests/test_tiling_check.py, Makefile, CHANGELOG.md
- Locations (modified): hooks/hooks.json (+.vault-meta/ staging), agents/wiki-ingest.md (single-writer rule for addresses), agents/wiki-lint.md (Mechanism 2+3 checks), skills/wiki-ingest/SKILL.md (aligned non-DragonScale wording), wiki/concepts/DragonScale Memory.md (M2 severity matches lint, M4 marked NOT IMPLEMENTED, seed page gets address c-000001), .claude-plugin/{plugin.json,marketplace.json} (1.4.2/1.4.3 → 1.5.0), README.md (11 skills + DragonScale callout), wiki/hot.md (refreshed for v1.5.0), .raw/.manifest.json (address_map now has DragonScale Memory.md → c-000001), .gitignore (.vault-meta/.tiling.lock + cache), .vault-meta/address-counter.txt (advanced to 2).
- Scope: resolve the 10 hold-ship items from the cross-phase audit. Add reproducible test harness (make test passes). Version-bump plugin.json and marketplace.json to 1.5.0. Create CHANGELOG.md. Refresh hot cache.
- Review rounds: codex 3.5a (5/5 accept on doc/agent fixes), codex final holistic (10/10 accept on audit items + 2 surgical regression fixes: wiki-ingest/wiki-lint non-DragonScale wording alignment, README skill count).
- Tests: `make test` runs 12 shell assertions (allocator) + 18 python assertions (tiling-check). All pass; no ollama dependency.
- Phase 3.5 complete. Repo state: 6 developer commits added this pass (f2e73c1, 2b49a0c, 8b28e48, 19ad7e4, 365f557, 2e7dd16). Total 39 commits ahead of origin/main. No push.

## [2026-04-24] save | DragonScale Phase 3 — semantic tiling MVP
- Type: skill update + new script + threshold state
- Locations: scripts/tiling-check.py (485 lines), .vault-meta/tiling-thresholds.json (seed defaults), skills/wiki-lint/SKILL.md (109-line Semantic Tiling section + item #10 in checks), wiki/concepts/DragonScale Memory.md (Mechanism 3 cost framing clarified)
- Scope: opt-in embedding-based duplicate detection via ollama nomic-embed-text. Default bands error>=0.90, review>=0.80, explicitly documented as conservative seeds (not literature-backed interpolation). Calibration procedure documented, not automated.
- Security: default OLLAMA_URL locked to 127.0.0.1; non-localhost requires --allow-remote-ollama flag. Symlinks and vault-root escapes rejected before file reads (prevents data exfil).
- Correctness: cache keyed on sha256(model+body); orphan GC on save; model-drift auto-invalidation on load.
- Concurrency: flock(LOCK_EX) on .vault-meta/.tiling.lock; per-PID temp file for atomic writes.
- Scale: warn >500 pages; hard-fail exit 4 at >5000 pages.
- Exit codes: 0/2/3/4/10/11 distinctly surfaced in wiki-lint wiring (not collapsed into "unknown").
- Review rounds: 4 codex exec adversarial passes covering security, cache correctness, feature gate, inclusion logic, scale, threshold honesty, concurrency, exit codes, model drift, terminology coupling.
  Round 1: 10 items -> 7 reject + 3 refine.
  Round 2: 6 accept + 4 still-reject (symlink ordering, prose sync, exit-code wiring, terminology in checklist + "no API cost" claim).
  Round 3: 3 accept + 1 still-reject (cost-framing phrasing).
  Round 4: accept.
- Final verdict: 10/10 accept.
- Phase 3 complete. All three DragonScale mechanisms that were in-scope for the initial spec are now shipped as opt-in features. Mechanism 4 (boundary-first autoresearch) was flagged as agenda-control out-of-scope per the v0.2 scope boundary; may or may not ship as a future phase.

## [2026-04-23] save | DragonScale Phase 2 — deterministic page addresses MVP
- Type: skill update + new script
- Locations: scripts/allocate-address.sh, skills/wiki-ingest/SKILL.md (Address Assignment section), skills/wiki-lint/SKILL.md (Address Validation section), wiki/concepts/DragonScale Memory.md (Mechanism 2 rewritten v0.2→v0.3), .vault-meta/address-counter.txt, .raw/.manifest.json (new)
- Scope: MVP address format `c-NNNNNN` (creation-order counter, zero-padded 6 digits). Rollout baseline 2026-04-23. Legacy pages exempt until deliberate backfill (future `l-` prefix). No content hash, no fold-ancestry encoding in the MVP (both deferred).
- Concurrency: atomic allocation via flock-guarded Bash helper. Counter recovery from max observed `c-` address, never silent reset to 1.
- Lint: post-rollout pages without address are errors; legacy pages without address are informational. Optional `.vault-meta/legacy-pages.txt` manifest grandfathers pages with missing/wrong `created:` metadata.
- Re-ingest idempotency: `.raw/.manifest.json` `address_map` preserves path→address mapping across re-ingests and renames.
- Naming: mechanism renamed from "content-addressable paths" to "deterministic page addresses" (the MVP is a counter, not a content hash; the old name was overclaim).
- Review rounds: 2 codex exec adversarial passes. Round 1: 8 rejects covering counter mutation, race conditions, uniqueness atomicity, missing-file recovery, terminology drift, silent regression path, legacy classification, re-ingest idempotency. Round 2: 7 accept + 1 reject (manifest.json absent). Round 3 (item 8 only): accept after creating `.raw/.manifest.json`.
- Final verdict: 8/8 accept.
- Phase 2 complete. Phase 3 (semantic tiling lint) gated on human approval.

## [2026-04-23] save | DragonScale Phase 1 — wiki-fold skill shipped
- Type: skill
- Location: skills/wiki-fold/SKILL.md, skills/wiki-fold/references/fold-template.md
- Scope: flat extractive fold over raw wiki/log.md entries. Dry-run default via Bash stdout (no Write tool, avoids PostToolUse hook residue). Structural idempotency via deterministic fold_id. Duplicate-range detection. Fold-of-folds explicitly out of scope.
- Review rounds: 3 codex exec adversarial passes. Round 1: 1 refine + 6 reject across 7 items (allowed-tools, hook-mutation risk, idempotency claim, dry-run faithfulness, children structure, Mechanism 1 coverage, auto-commit conflict). Round 2: 6 accept + 1 reject (25/26 count inversion). Round 3 (item 4 only): accept.
- Final verdict: 7/7 accept.
- Dry-run artifact: /tmp/wiki-fold-dry-run-v2.md (not committed). fold_id: fold-k3-from-2026-04-10-to-2026-04-23-n8.
- Phase 1 complete. Phase 2 (content-addressable paths) gated on human approval.

## [2026-04-23] save | DragonScale Memory v0.2 — post-adversarial-review
- Type: concept revision
- Location: wiki/concepts/DragonScale Memory.md
- Review: codex exec adversarial review rejected all 7 load-bearing claims in v0.1
- Changes: weakened LSM analogy, removed strong prompt-cache claim, replaced 0.85 threshold with calibration procedure, justified 2^k as MVP convenience, acknowledged scope-boundary leak for boundary-first autoresearch, added Operational Policies section (retention/tombstones/versioning/conflict/concurrency/provenance/ACL), tagged claims as [sourced]/[derived]/[conjecture], narrowed tagging scope per re-review
- Re-review result: 7/7 accepted (after one surgical fix on tagging-scope language)
- Phase 0 complete. Phase 1 (wiki-fold skill) gated on human approval.

## [2026-04-23] save | DragonScale Memory — Phase 0 design doc (proposed)
- Type: concept
- Location: wiki/concepts/DragonScale Memory.md
- From: brainstorming session on applying Heighway dragon curve properties to LLM wiki memory architecture
- Scope: memory-layer only, NOT agent reasoning. Four mechanisms: (1) fold operator (LSM-style exponential compaction at 2^k log entries), (2) content-addressable page paths for prompt-cache stability, (3) semantic tiling lint (embedding-based dedup, 0.85 cosine threshold), (4) boundary-first autoresearch scoring
- Status: proposed. Phase 0 pending codex adversarial review. Phase 1+ (fold skill, address anchors, tiling lint, boundary score) gated on review pass.
- Primary sources verified: Dragon curve (Wikipedia, boundary dim 1.523627086), Regular paperfolding sequence (OEIS A014577), LSM trees (arXiv 2504.17178, LevelDB 10x level ratio), MemGPT (arXiv 2310.08560), Anthropic prompt caching docs (5min/1hr TTL, 20-block lookback)
- Links updated: wiki/concepts/_index.md, wiki/index.md

## [2026-04-15] save | Claude SEO v1.9.0 Slides and GitHub Release
- Type: session
- Location: wiki/meta/2026-04-15-slides-and-release-session.md
- From: built 15-slide HTML presentation deck (v190.html), fixed hardcoded path in release_report.py, pushed 68 files to GitHub, tagged v1.9.0, created GitHub release with PDF asset
- Key lessons: Path.home() not hardcoded paths, git pull --rebase before big pushes, Chrome blocks file:// cross-origin images, .claude/ always in .gitignore
- Release: https://github.com/AgriciDaniel/claude-seo/releases/tag/v1.9.0

## [2026-04-15] save | Claude SEO v1.9.0 Release Report — PDF Complete
- Type: session
- Location: wiki/meta/2026-04-15-release-report-session.md
- From: full session completing the v1.9.0 PDF release report. Dark theme, 13 pages, 1.53 MB. Fixed logo (double-space filename), empty spaces, page-break orphans, file:// URL encoding.
- Key fixes: `urllib.parse.quote()` for file:// URIs; `display:table-cell` is atomic in WeasyPrint (no page-break); fixed `height:297mm` causes empty space; replaced orphan tables with paragraphs
- Challenge v2 added: keyword LEADS, $600 prize pool, deadline April 28
- Output: `~/Desktop/Claude-SEO-v1.9.0-Release-Report.pdf`

## [2026-04-14] save | Claude SEO v1.9.0 — Pro Hub Challenge Integration Session
- Type: session + 4 concept pages + 1 entity page
- Location: wiki/meta/2026-04-14-claude-seo-v190-session.md
- From: full v1.9.0 implementation session — reviewed 5 community submissions, integrated 4 new skills (seo-cluster, seo-sxo, seo-drift, seo-ecommerce), enhanced seo-hreflang, added DataForSEO cost guardrails
- Pages created: [[2026-04-14-claude-seo-v190-session]], [[Claude SEO]], [[Pro Hub Challenge]], [[Semantic Topic Clustering]], [[Search Experience Optimization]], [[SEO Drift Monitoring]]
- Review rounds: 4 (code review x3 + cybersecurity audit). Score: 87 → 93 → 97 → 85 security
- Key learnings: always verify subagent output (40-line count error caught), insertion-point bugs caught by max-effort plan review, pre-existing security debt identified (10 of 15 findings)

## [2026-04-14] save | SVG Diagram Style Guide
- Type: concept
- Location: wiki/concepts/SVG Diagram Style Guide.md
- From: extracted design tokens from 17 production SVGs in claude-ads/assets/diagrams/
- Covers: colors, typography, layout primitives, card patterns, arrow connectors, numbered circles, file naming

## [2026-04-14] save | Community CTA Footer Rollout
- Type: decision
- Location: wiki/meta/2026-04-14-community-cta-rollout.md
- From: session adding Skool community footer to 6 skill repos (claude-ads, claude-seo, claude-obsidian, claude-blog, banana-claude, claude-cybersecurity)
- Key insight: frequency calibration per tool type; single-point orchestrator instruction pattern

## [2026-04-10] save | Backlink Empire - Blog Posts, Karpathy Gist, GitHub Cross-Linking
- Type: session
- Location: wiki/meta/2026-04-10-backlink-empire-session.md
- From: full session covering blog creation (claude-obsidian + claude-canvas), Karpathy gist comment, 26 GitHub README updates with Author/community/backlink sections, homepage URLs on 10 repos, topics on 25 repos, rankenstein.pro backlinks on 5 SEO repos
- Blog posts: agricidaniel.com/blog/claude-obsidian-ai-second-brain, agricidaniel.com/blog/claude-canvas-ai-visual-production
- Impact: ~87 new backlinks from DA 96 github.com, 6 rankenstein.pro backlinks, 25 Skool community links

## [2026-04-08] save | claude-obsidian v1.4 Release Session
- Type: session
- Location: wiki/meta/claude-obsidian-v1.4-release-session.md
- From: full release cycle covering v1.1 (URL/vision/delta tracking, 3 new skills), v1.4.0 (audit response, multi-agent compat, Bases dashboard, em dash scrub, security history rewrite), and v1.4.1 (plugin install command hotfix)
- Key lessons: plugin install is 2-step (marketplace add then install), allowed-tools is not valid frontmatter, Bases uses filters/views/formulas not Dataview syntax, hook context does not survive compaction, git filter-repo needs 2 passes for full scrub

## [2026-04-08] ingest | Claude + Obsidian Ecosystem Research
- Type: research ingest
- Source: `.raw/claude-obsidian-ecosystem-research.md`
- Queries: 6 parallel web searches + 12 repo deep-reads
- Pages created: [[claude-obsidian-ecosystem]], [[cherry-picks]], [[claude-obsidian-ecosystem-research]], [[Ar9av-obsidian-wiki]], [[Nexus-claudesidian-mcp]], [[ballred-obsidian-claude-pkm]], [[rvk7895-llm-knowledge-bases]], [[kepano-obsidian-skills]], [[Claudian-YishenTu]]
- Key finding: 16+ active Claude+Obsidian projects; 13 cherry-pick features identified for v1.3.0+
- Top gap confirmed: no delta tracking, no URL ingestion, no auto-commit

## [2026-04-07] session | Full Audit, System Setup & Plugin Installation
- Type: session
- Location: wiki/meta/full-audit-and-system-setup-session.md
- From: 12-area repo audit, 3 fixes, plugin installed to local system, folder renamed

## [2026-04-07] session | claude-obsidian v1.2.0 Release Session
- Type: session
- Location: wiki/meta/claude-obsidian-v1.2.0-release-session.md
- From: full build session — v1.2.0 plan execution, cosmic-brain→claude-obsidian rename, legal/security audit, branded GIFs, PDF install guide, dual GitHub repos


- Source: `.raw/` (first ingest)
- Pages updated: [[index]], [[log]], [[hot]], [[overview]]
- Key insight: The wiki pattern turns ephemeral AI chat into compounding knowledge — one user dropped token usage by 95%.

## [2026-04-07] setup | Vault initialized

- Plugin: claude-obsidian v1.1.0
- Structure: seed files + first ingest complete
- Skills: wiki, wiki-ingest, wiki-query, wiki-lint, save, autoresearch
