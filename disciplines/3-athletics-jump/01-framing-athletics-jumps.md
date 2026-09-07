# Framing Sheet — Athletics: Jumps (High Jump, Pole Vault, Long Jump, Triple Jump)
**Week 38 · Sep 7-13, 2026 · LA2028**

## 1. What "performance" means in this discipline
The jumps group four distinct events split into two families:
- **Horizontal jumps** (Long Jump, Triple Jump): performance is the **distance** covered from the take-off board to the nearest landing mark, measured in meters/centimeters. Athletes get 3 attempts in qualification (or a direct qualifying distance) and up to 6 in the final; only the single best legal attempt counts. A jump is void ("foul") if the athlete oversteps the take-off board.
- **Vertical jumps** (High Jump, Pole Vault): performance is the **highest bar height cleared**, with the bar progressively raised. Athletes get 3 attempts per height before elimination; ties are broken by fewest failed attempts overall, then fewest jumps taken at the winning height.

All four are purely **measured outcomes** (distance or height), not judged — but each has a strong **technical/biomechanical component** (approach-run speed, take-off angle, pole-bend energy transfer for vault) that makes them a rich subject for kinematic analysis, not just a results table.

## 2. LA2028 qualification calendar
- **Discipline schedule**: Athletics will be held during the **first week of the Games** (a historic change from the original plan), from **July 15-30, 2028**, at the **LA Memorial Coliseum** — the first stadium ever to host athletics at three separate Olympic Games (1932, 1984, 2028).
- **Qualification system**: as of this writing, World Athletics has not yet published the detailed LA28 entry-standards and quota document (several other federations, e.g. swimming, gymnastics, weightlifting, have already released theirs). Based on the established pattern from Tokyo 2020 and Paris 2024, expect a **mixed system of entry standards ("A" times/marks) and World Athletics Ranking positions**, with a target close to a 50/50 split between the two pathways, and a qualification window likely running from mid-2027 to mid-2028.
- **To confirm once published**: exact entry-standard marks for each jump event, total quota per event, and the precise qualification window dates.

## 3. Governing bodies and official sources
| Body / platform | Role | Link |
|---|---|---|
| **World Athletics** | International federation, calendar, entry standards, rankings, results | worldathletics.org |
| **World Athletics Research Centre** | Publishes official biomechanical reports after major championships | worldathletics.org/development/research |
| **LA28** | Organizing committee, discipline and venue info | la28.org |
| **Olympics.com / IOC** | Official qualification system documents (once published), news | olympics.com |
| **Wikipedia** | Archived results and standards from past World Championships/Olympics | en.wikipedia.org |
| **World Athletics Ranking system** | Live points-based ranking used for non-standard qualification places | worldathletics.org/world-rankings |

## 4. Performance indicators to track (leads for the analysis)
- Personal best and season's best progression over the last 2-3 seasons
- Foul/no-jump rate in horizontal jumps (technical consistency vs. risk-taking on the approach)
- First-attempt success rate at entry heights in High Jump/Pole Vault (efficiency, fewer "wasted" jumps)
- Gap between qualification-round mark and final mark (peaking ability under pressure)
- Age at first major-championship final vs. current age
- Approach-run speed trends where available (a known strong predictor in horizontal jumps per biomechanical literature)

## 5. Resources to go deeper
- World Athletics Research Centre biomechanical reports — official kinematic analyses of every finalist at recent World Championships, covering approach speed, take-off angle, and flight mechanics for each jump event
- Academic literature is unusually rich for this discipline family compared to newer Olympic sports: search terms like *"long jump biomechanics take-off velocity"*, *"pole vault energy transfer"*, *"high jump approach run kinematics"* return decades of peer-reviewed material
- Wikipedia result pages for recent World Championships and Olympic Games jump finals (attempt-by-attempt marks, useful as a raw data source)
- Note: a 2024 arXiv study applied quantile random forest and explainable-AI techniques directly to World Athletics long jump biomechanical data

## 6. Notes / research hypotheses
- Discipline with a genuinely large, decades-deep official biomechanical dataset behind it (World Athletics Research Centre reports since 1995) — a good opportunity to go beyond results-only analysis and incorporate technical/kinematic variables if time allows.
- Four events in one week means a choice to make: either produce one combined "jumps" analysis with a shared indicator framework, or split into four shorter athlete-level case studies.
- Horizontal vs. vertical jumps have different failure modes (fouls vs. missed heights) — keep them as separate variables rather than merging into one "success rate" metric.