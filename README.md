# Derelict (Working Title)

**A solo sci-fi / cosmic horror journaling RPG**

**Live site:** [https://theoryderailed.github.io/derelict-/](https://theoryderailed.github.io/derelict-/)

> **Note:** The name *Derelict* is a temporary placeholder. A final name will be chosen to avoid collision with existing titles.

You are alone on a damaged or abandoned vessel, station, or colony. Something is wrong with it, and it is getting worse. You keep a log while you try to survive, understand what happened, or simply hold on.

The game is designed to be extremely simple:
- One standard deck of playing cards (Jokers removed)
- One six-sided die
- A journal

Anyone should be able to start playing in under five minutes.

---

## Quickstart

1. Create a short character description (name + role + how you ended up alone).
2. Set three tracks:
   - **Integrity** = 6
   - **Mind** = 6
   - **Hope** = 4
3. Shuffle a standard deck of cards.
4. Write your opening log entry.
5. Begin the core loop (see [RULES.md](RULES.md)).

---

## Repository Structure

```
/
├── RULES.md
├── README.md
├── CHANGELOG.md
├── COPYRIGHT.md
└── modules/
    ├── 01-cs-orpheus/
    │   └── module.md
    ├── 02-deadweight/
    │   └── module.md
    ├── 03-static/
    │   └── module.md
    ├── 04-murray/
    │   └── module.md
    ├── 05-echo/
    │   └── module.md
    ├── 06-gantry/
    │   └── module.md
    ├── 07-dead-haul/
    │   ├── module.md
    │   ├── playthrough.md
    │   └── faq.md
    ├── 08-hard-vacuum/
    │   ├── module.md
    │   ├── playthrough.md
    │   └── faq.md
    ├── 09-quarantined/
    │   └── module.md
    └── 10-covenant/
        └── module.md
```

Each module lives in its own directory.

- `module.md` — full rules for that scenario
- `playthrough.md` — short example playthrough (when present)
- `faq.md` — focused FAQ for the module’s unique tools (when present)

---

## Current Modules

| #  | Module            | Focus                                      | Playthrough + FAQ |
|----|-------------------|--------------------------------------------|-------------------|
| 01 | CS Orpheus        | Cosmic rewriting / body horror             | —                 |
| 02 | Deadweight        | Unreliable AI + three scenario locks       | —                 |
| 03 | Static            | Signal lure / rescuer ambiguity            | —                 |
| 04 | Murray            | Time-loop alien escape                     | —                 |
| 05 | Echo              | Identity A/B testing + journal warfare     | —                 |
| 06 | Gantry            | Industrial cosmic horror + social pressure | —                 |
| 07 | Dead Haul         | Pulp-noir serial killer investigation      | Yes               |
| 08 | Hard Vacuum       | Environmental survival, hold until rescue  | Yes               |
| 09 | Quarantined       | Medical horror, moral uncertainty          | —                 |
| 10 | Covenant          | Generation ship, living religion, outcast  | —                 |

---

## Design Goals

- Extremely low barrier to entry
- Strong focus on isolation and cosmic dread
- Journaling as the primary output
- Short, complete arcs of deterioration
- Module-specific tools that do not break the core engine

---

## License and Attribution

This work is licensed under **CC BY-NC 4.0** (Attribution-NonCommercial).

You may freely play, share, and adapt it for non-commercial purposes, but you must give credit to the creator. Commercial use is not permitted without permission.

See [COPYRIGHT.md](COPYRIGHT.md) for full details.
