# Called Shots — Precision Strikes

> *"Every swing is a choice. Strike at the body, and you may wound. Strike at the weakness, and you may decide the battle."*

---

## 1. Core Rules

### Declaration
Called Shots must be declared **before** the attack roll is made. Once declared, the penalty applies to that attack regardless of outcome. If you already have Disadvantage on the attack roll, Called Shot penalties still apply — they stack, making precision strikes riskier under pressure.

### Access
- **Any character** may target **basic areas** (Head, Arms, Legs, Torso) with any weapon or spell they are **proficient** with.
- **Advanced areas** (Eye, Hand, Throat, Wing, Tail) also require proficiency with the weapon or spell being used.

### Attack Penalty
A flat penalty is applied to the attack roll based on the targeted location. If the attack misses, no special effect occurs — only damage on a hit triggers the Called Shot effect.

### Passive Perception Detection
When a Called Shot is declared, the defender's **Passive Perception** is automatically compared to the **Detection DC**. No action or roll is required from the defender.

**Detection DC = 10 + Attacker's Attack Bonus − Called Shot Penalty**

More extreme Called Shots (e.g., Head −5) are easier to spot because the attacker must telegraph their aim more obviously.

| Result | Effect |
|---|---|
| **Passive Perception ≥ Detection DC** | Defender gains **Advantage on their Evasion roll** and knows which body part is being targeted. |
| **Passive Perception < Detection DC** | Defender rolls Evasion normally and does not know the targeted location. |

### Resolution
On a hit, roll damage normally. The target then makes a **saving throw** to resist the Called Shot effect. If the save fails, the effect applies (duration as listed per location). If the save succeeds, only damage is dealt.

On a **glancing blow**, damage is halved then DR applied. If any damage remains after DR, the Called Shot effect still applies. If DR reduces the glancing blow damage to exactly 0, no effect triggers.

### Critical Hits and Called Shots
If a Called Shot attack results in a **critical hit** (Nat 20 on the attack roll), the target's saving throw against the Called Shot effect is made at **disadvantage**. The critical hit does not automatically apply the effect — the save still occurs, but the odds are greatly worsened.

### Once Per Attacker Per Turn
Only **one Called Shot effect** may apply per attacker per turn, regardless of how many attacks or spells land. If multiple hits could trigger Called Shot effects in the same turn, the attacker chooses which effect applies — all other hits deal damage only. This rule is core, not optional.

> **Example:** A Sorcerer fires Scorching Ray at three targets, declaring leg shots on each. Two rays hit. Only one leg-shot effect applies — the attacker chooses which target makes the Dexterity save. The second target takes damage only.

### Momentum Synergy
- Called Shot **hits** where the target **fails the save** → **+2 Momentum** instead of +1.
- Called Shot hits where the target **succeeds the save** → normal +1 Momentum for the hit.
- Called Shot **misses** → −1 Momentum as normal.

### Monster Immunities and Anatomy
Creatures without the relevant anatomy (oozes, swarms, elementals, certain constructs) may be immune to specific Called Shots at GM discretion. Effects should be adapted to fit the creature's nature:
- "Eye" → "Sensory core"
- "Leg" → "Locomotive appendage"
- "Throat" → "Resonant chamber" (for sound-based creatures)

---

## 2. Target Locations

### Basic Areas
*Available to any character proficient with the weapon or spell.*

| Target | Penalty | Save | Effect on Failed Save |
|---|---|---|---|
| **Head** | −5 | CON | Stunned/disoriented: Disadvantage on all attacks + lose Reaction until end of next turn. |
| **Arms** | −2 | STR | Disarm (drop held item) or impose −2 to attack rolls for 1 round. Attacker's choice. |
| **Legs** | −2 | DEX | Speed reduced to 0 until end of next turn, or fall Prone. Attacker's choice. |
| **Torso** | 0 | — | Standard damage. No special effect. |

### Advanced Areas
*Requires proficiency with the weapon or spell used.*

| Target | Penalty | Save | Effect on Failed Save |
|---|---|---|---|
| **Eye** | −7 | CON | Blinded until end of next turn. |
| **Hand** | −4 | DEX | Drop held object or fail somatic spell component (attacker's choice). |
| **Throat** | −6 | INT | Silenced for 1 turn — no verbal spells, no command words, no shouts. |
| **Wing** | −3 | DEX | If airborne, fall immediately or lose flight for 1d4 rounds (attacker's choice). |
| **Tail** | −3 | DEX | Lose balance; fall prone if save fails. |

---

## 3. Weapon Skills and Called Shots on the Same Attack

A Weapon Mastery Skill and a Called Shot may both be declared on the same attack. If both would impose a condition or require a saving throw, only **one saving throw** occurs. The attacker chooses which effect the save resists — the other effect applies automatically regardless of the save result.

> **Example:** A Fighter declares a Called Shot to the legs (DEX save or prone) and applies Hamstring (CON save or speed halved) on the same hit. The attacker chooses that the DEX save resists the prone effect. Whether the save succeeds or fails, the speed reduction from Hamstring applies automatically.

This rewards tactical layering without removing all defensive agency from the target.

---

## 4. DCS Integration

### DR Interaction
Called Shots bypass the distributed protection of full armour by targeting a specific location:

| Armour | Total DR (Standard Attack) | Arm DR (Called Shot) | DR Bypassed | Worth the −2 Penalty? |
|---|---|---|---|---|
| Light | 5 | 1 | 4 | Situational |
| Medium | 10 | 2 | 8 | Usually |
| Heavy | 15 | 3 | 12 | **Almost always** |

Against opponents with Total DR 10+, Called Shots to arms or legs commonly deal more total damage despite the accuracy penalty.

> **Unarmoured Targets:** If the targeted body part is unarmoured (DR 0), the target's saving throw against the Called Shot effect is made at **disadvantage**. Exception: creatures with Unarmoured Defence treat their unarmoured state as armoured for this purpose.

> **Heavily Armoured Targets:** DR is applied first. If DR reduces damage to 0 on a Called Shot, the effect does not trigger — no damage means no effect.

### Evasion Interaction
Called Shots roll against Evasion normally. On a glancing blow (tie), damage is halved then DR applied — but the Called Shot effect **still applies** if any damage gets through after DR.

### Momentum Integration
- At **+3 Momentum**, defenders roll Called Shot saving throws with **advantage** — high rhythm makes you harder to pin down.
- At **−2 Momentum**, defenders roll Called Shot saving throws with **disadvantage** — a struggling target is easier to exploit.

### Injury System Integration
If a Called Shot drives a target through an HP threshold, **both systems trigger**:
1. Resolve the Called Shot effect (saving throw).
2. Roll on the appropriate Injury table.

These stack — a Leg Shot can knock a target prone *and* trigger a Broken Bone result from the Injury table. The mechanical condition and the lasting wound reinforce each other.

### Insightful Combatant (Optional Rule)
A character may use **Insight** instead of Passive Perception against humanoid foes they have fought for more than 2 rounds, or against those attempting feints or disinformation tactics. Rangers may use Insight against favoured enemies. Investigators may use Insight against any humanoid.

---

## 5. Class Features and Called Shots

| Class / Subclass | Head Penalty | Arms Penalty | Legs Penalty | Special |
|---|---|---|---|---|
| **Rogue** | −3 | −1 | −1 | Sneak Attack applies to called shots and ignores DR. Called Shot penalty reduced by 2 when qualifying for Sneak Attack. |
| **Rogue: Assassin** | 0 (surprised targets) | 0 (surprised targets) | 0 (surprised targets) | No penalties against surprised targets. Critical hits against surprised targets impose Called Shot effects without a save. Ignores all DR on surprised targets on the first turn. |
| **Monk** | −3 | −1 | −1 | Pressure Point Strikes: Head → Blinded; Arms → Disadvantage on attacks; Legs → cannot Dash. |
| **Fighter: Battle Master** | Variable | Variable | Variable | Spend a Superiority Die to reduce the Called Shot penalty by the die result. |
| **Fighter: Champion** | −4 | −2 | −2 | Critical hits on called shots impose the Called Shot effect with the saving throw at disadvantage. |
| **Barbarian (while Raging)** | −5 | 0 | 0 | Called shots to arms or legs have no penalty while Raging. |
| **Ranger: Hunter's Mark** | −3 | −1 | −1 | Reduces penalties; reduces target DR by the Ranger's Wisdom modifier; marked target rolls Called Shot Perception checks at disadvantage. |
| **Ranger: Favoured Enemy** | −2 | 0 | 0 | Reduces penalties against favoured enemies. Stacks with Hunter's Mark. |
| **Ranger: Mark + Favoured Synergy** | 0 | 0 | 0 | Combines both: penalty-free called shots, DR reduced by Wisdom modifier + 1, +1 damage die. |
| **Ranger: Gloom Stalker** | −2 | 0 | 0 | Round 1: no Called Shot penalties. Called shots in dim light/darkness impose disadvantage on target's save. |
| **Paladin: Oath of Vengeance** | −2 | −1 | −1 | Vow of Enmity: one attack per round against the marked target ignores Called Shot penalties entirely. |
| **Paladin: Oath of Conquest** | −3 | −1 | −1 | Leg shots force a Wisdom save or restrain the target (instead of just speed reduction). |
| **Bard: College of Swords** | −2 | −1 | −1 | Called shots during a Blade Flourish have no penalties. |
| **Hexblade Warlock** | −3 (cursed target) | 0 (cursed target) | 0 (cursed target) | Penalties reduced by 2 against cursed targets. Adds necrotic damage equal to Charisma modifier. |
| **Bladesinger Wizard** | −2 | −1 | −1 | While in Bladesong, called shots add bonus damage equal to the spell slot level (+1 per level). |

---

## 6. Called Shot Feats

| Feat | Prerequisites | Effect |
|---|---|---|
| **Sharpshooter** | Ranged weapon proficiency | Reduce ranged Called Shot penalties by 2. Crits on ranged called shots impose disadvantage on the save. Ignore long-range penalties for called shots. |
| **Great Weapon Master** | Heavy melee weapon proficiency | Declare a called shot alongside Power Attack (−5/+10). Crits on called shots deal +1 weapon die and the save is automatically failed. Kill with a called shot → make another called shot as a bonus action. |
| **Crossbow Expert** | Crossbow proficiency | Ignore Called Shot penalty on the first attack each turn. Called shots with crossbows bypass 1 DR at the targeted location. |
| **Martial Adept** | None | Pinpoint Strike: expend a Superiority Die to reduce Called Shot penalty by the die roll. Nerve Strike: expend a Superiority Die after a Called Shot hit to impose disadvantage on the target's next attack. |
| **Sentinel** | None | Sentinel reaction attacks may be declared as Called Shots. Leg shots reducing speed to 0 keep it at 0 until end of your next turn regardless of other effects. |
| **Mobile** | None | After a leg shot (hit or miss), move 10 ft without provoking opportunity attacks. Reduce leg shot penalty by 1. |
| **Lucky** | None | Luck Points may reroll a Called Shot attack without retaining the penalty. Luck Points may force a target to reroll their Called Shot saving throw. |
| **Piercer** | Piercing weapon proficiency | Crits with piercing weapons on called shots: reroll one damage die and add 2 damage. Called shots with piercing weapons bypass 2 DR at the targeted location. |
| **Crusher** | Bludgeoning weapon proficiency | Reduce Head and Arms Called Shot penalties by 2. On a called shot kill with a bludgeoning weapon, push a creature within 5 ft up to 10 ft away. |
| **Slasher** | Slashing weapon proficiency | Called shots to arms or legs with slashing weapons reduce movement by an additional 10 ft. A called shot hit applies 1d6 ongoing slashing damage at the start of the target's next turn. |
| **Alert** | None | Advantage on Passive Perception checks to detect incoming Called Shots. If a Called Shot is detected, move 5 ft as a reaction without provoking opportunity attacks. |
| **Shield Master** | Shield proficiency | Reduce Called Shot penalty by 2 for attacks targeting your torso or arms. After successfully blocking a called shot with a shield, make one melee attack against the attacker as a reaction. |
| **Tavern Brawler** | None | You are treated as proficient with improvised weapons for the purpose of Called Shots. Improvised weapon Called Shots incur no penalties. Grappled targets may be targeted with Called Shots at no penalty. |
| **Sniper's Precision** *(New)* | Ranged weapon proficiency | Reduce all ranged Called Shot penalties by 2. Critical range expands to 19–20 on called shots. Crits on called shots impose disadvantage on the target's save. |
| **Masterful Strikes** *(New)* | None | Reduce Head penalty by 1 and Arms/Legs penalties by 2. Crits on called shots deal +1d8 damage of the same type. Advantage on attack rolls for called shots against creatures you've damaged this round. |

---

## 7. Combat Flow

| Step | Action |
|---|---|
| **1. Declare** | Announce the Called Shot and targeted body part before rolling. |
| **2. Detection** | Compare defender's **Passive Perception** to Detection DC (10 + Attack Bonus − Penalty). Automatic — no action required. Grant advantage on Evasion if detected. |
| **3. Attack Roll** | Roll `1d20 + attack bonus − Called Shot penalty`. |
| **4. Evasion Roll** | Defender rolls Evasion against the attack roll as DC. |
| **5. Damage** | On a hit, roll damage. On a glancing blow, halve first then apply location DR. |
| **6. Effect** | Target makes a saving throw. On a crit, the save is at **disadvantage**. On failure, apply the Called Shot effect. If DR reduces a glancing blow to 0, no effect triggers. |
| **7. Momentum** | Hit + failed save = +2 MS. Hit + save succeeded = +1 MS. Miss = −1 MS. |

---

## 8. Examples

### Scenario 1: Ranger with Hunter's Mark — Leg Shot

A Ranger (Wisdom modifier +3) marks a goblin and declares a called shot to its legs.

1. **Attack Roll:** `1d20 + 6 (Dex + PB) − 1 (leg penalty reduced by Hunter's Mark)` = 17. Hits.
2. **Damage:** `1d8 (longbow) + 1d6 (Hunter's Mark)` = 12 damage. Goblin's DR reduced by 3 (Wisdom modifier) → full damage applies.
3. **Effect:** Goblin makes a **DEX save (DC 14)** and fails → knocked prone.
4. **Momentum:** Ranger gains +2 MS.

---

### Scenario 2: Assassin's Critical Called Shot

An Assassin targets the head of a surprised guard.

1. **Attack Roll:** `1d20 + 7` with no penalty (Assassinate removes penalties against surprised targets). Critical hit on the roll.
2. **Damage:** `1d8 + 4d6 (Sneak Attack)` — all dice doubled on a crit. All damage ignores DR.
3. **Effect:** Guard makes a **CON save at disadvantage** (critical hit). On failure → stunned.

---

### Scenario 3: Scorching Ray — Once Per Turn Rule

A Sorcerer fires Scorching Ray at three orcs, declaring leg shots.

1. **Attack Rolls:** Two rays hit. One misses.
2. **Effect:** Only **one leg-shot effect** applies this turn. Sorcerer chooses the first orc — it makes a **DEX save (DC 14)** and fails → knocked prone. The second orc takes damage only.

---

### Scenario 4: Weapon Skill + Called Shot on Same Attack

A Fighter declares a Leg Called Shot (DEX save or prone) and triggers Hamstring (CON save or speed halved) on the same hit.

1. **Attack lands.** Both effects would normally apply separately.
2. **One save.** The Fighter chooses: the DEX save resists the prone effect.
3. **Orc rolls DEX save.** It **fails** → falls prone.
4. **Hamstring applies automatically** regardless of save result → speed also halved.
5. **Momentum:** +2 MS for the called shot with failed save.

---

### Scenario 5: Rogue Headshot

A Rogue targets a bandit's head.

1. **Attack Roll:** `1d20 + 6 − 3 (head penalty reduced by Rogue feature)` = 17. Hits.
2. **Damage:** `1d8 + 2d6 (Sneak Attack)` — ignores DR entirely.
3. **Effect:** Bandit makes a **CON save (DC 14)** → fails → stunned until Rogue's next turn.
4. **Momentum:** Rogue gains +2 MS.

---

### Scenario 6: Eldritch Blast Headshot

A Warlock fires Eldritch Blast at a bandit captain, declaring a head shot.

1. **Attack Roll:** `1d20 + 7 − 5 (head penalty)` = 16. Hits.
2. **Damage:** `1d10` = 8 force damage.
3. **Effect:** Captain makes a **CON save (DC 15)** → fails → stunned.

---

### Scenario 7: Glancing Blow — Effect Still Applies

A Fighter makes an arm shot against a guard. The Evasion roll ties the attack roll — a glancing blow.

1. **Damage:** `1d8 + 3` = 10 damage. Halved to 5, then minus Arms DR 2 = **3 damage**.
2. **Effect:** Damage got through (3 > 0), so the Called Shot effect still applies. Guard makes a **STR save** → fails → drops sword.

---

### Scenario 8: Glancing Blow — Effect Negated by DR

Same scenario but the guard is in heavy armour. Arms DR 3.

1. **Damage:** 10 damage. Halved to 5, then minus Arms DR 3 = **2 damage**.
2. **Effect:** Still triggers — 2 damage got through. Guard makes the STR save.

*(If DR had reduced the glancing blow to exactly 0, no effect would trigger.)*
