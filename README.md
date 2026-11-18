# plotline-architect: Pacing & Milestones (`SUBVERTED_HARRY`)

[![Repo Type: Narrative Architecture](https://img.shields.io/badge/Repo-Plotline%20Architect-teal.svg)](https://github.com/ImmortalWiz/plotline-architect)
[![Timeline Engine: 4 Eras](https://img.shields.io/badge/Eras-4%20Macro%20Arcs-orange.svg)](https://github.com/ImmortalWiz/plotline-architect)
[![Parent Engine](https://img.shields.io/badge/Parent-harry--potter--and--the--magical--reality--check-blue.svg)](https://github.com/ImmortalWiz/harry-potter-and-the-magical-reality-check)

The **Plotline Architect (`plotline-architect`)** repository maintains the absolute temporal continuity and structural pacing of the universe across four epic narrative eras. It acts as the blueprint engine that feeds into `scene-blueprints` and `prose-drafts`.

---

## 📅 The Four Master Eras

```
+-----------------------------------------------------------------------------------+
| ERA 01: The Shield of Fame (Years 1–4)                                           |
| Starved ego latches onto celebrity; surviving on pure luck and desperate help.    |
+-----------------------------------------------------------------------------------+
                                          │
                                          ▼
+-----------------------------------------------------------------------------------+
| ERA 02: Coward's Flight (Years 5–7 & Exile)                                       |
| The graveyard shatters the shield; Harry flees Britain, hunted globally as prey.  |
+-----------------------------------------------------------------------------------+
                                          │
                                          ▼
+-----------------------------------------------------------------------------------+
| ERA 03: The Hardened Guerrilla                                                    |
| Returns as a transactional mercenary leader; savage hit-and-run warfare; ash victory. |
+-----------------------------------------------------------------------------------+
                                          │
                                          ▼
+-----------------------------------------------------------------------------------+
| ERA 04: The Slow Thaw                                                             |
| Fortified isolation; dismantling paranoia and hyper-vigilance; rehabilitation.    |
+-----------------------------------------------------------------------------------+
```

---

## 📂 Directory Layout & Schema

```
plotline-architect/
├── master_chronology.md                # Global timeline cross-referencing Muggle and magical history
├── era_01_shield_of_fame/
│   ├── macro_arc_blueprint.md          # Pacing curve and escalation across Years 1-4
│   └── book_01_the_fame_shield/
│       ├── book_milestones.md          # 5-point structural milestones (Inciting, Climax, etc.)
│       ├── ch01_outline.md             # Chapter 1 narrative beats
│       ├── ch02_outline.md             # Chapter 2 narrative beats
│       └── ch03_outline.md             # Chapter 3 narrative beats
├── era_02_cowards_flight/
│   ├── macro_arc_blueprint.md          # Pacing curve for the Graveyard break and international exile
│   └── book_03_the_flight_of_the_savior/
│       ├── book_milestones.md
│       └── ch01_outline.md
├── era_03_hardened_guerilla/
│   └── macro_arc_blueprint.md          # Guerrilla warfare doctrine and final fall of the Ministry
└── era_04_slow_thaw/
    └── macro_arc_blueprint.md          # Epilogue arcs and psychological dismantling
```

---

## 📝 Chapter Outline Schema (`chXX_outline.md`)

Every chapter outline must follow this standardized schema:

```markdown
# Chapter [Number]: [Title]

## 1. Narrative Purpose
* The primary structural shift or thematic reveal of this chapter.

## 2. Character Objectives
* **Harry:** What he wants vs. what he is avoiding.
* **Supporting Characters:** What they want and their point of friction.

## 3. Beat Sheet
1. **Hook:** Opening state of tension.
2. **Development:** Escalation or false comfort.
3. **Turn:** The complication or unmasking.
4. **Resolution/Cliffhanger:** The forward momentum into the next chapter.

## 4. Continuity & Gap Flags
* Verified against `war-entities`: Active gaps tested in this chapter.
```

---

## 🤖 Guide for AI Context Engines

* **Sequencing Enforcement:** Always verify that an event in `era_02` does not reference character states that belong to `era_03`.
* **Outlining Before Drafting:** Never generate scene dialogue or draft manuscripts without an existing outline in `plotline-architect/`.
* **Milestone Integrity:** Chapters must advance the structural goals defined in `book_milestones.md`.
