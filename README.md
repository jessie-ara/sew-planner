# Sewing planner

Decide before doing. Record only what makes the next project faster.

| Stage | Decide | Gate (tick all to clear) |
|---|---|---|
| **1 Prep** | Pattern, view, size, fabric. Read-through, unknowns, measurements. Reference sheet. | Reference sheet done |
| **2 Source** | Check stash, buy the rest. Shopping list builds itself from Prep. | Everything in hand |
| **3 Fit** | Toile, or baste-and-try if skipping. | Adjustments noted on pattern |
| **4 Cut** | Grainline, layout, cutting method, markings. | Pieces marked and labelled |
| **5 Sew** | Order of operations. Blocker log. | Finishing done, all operations ticked |
| **6 Review** | Problem → fix, keep doing, change next time. | At least one review field filled |

## Why this order

Method choices change what you buy (seam finish, hem, interfacing, thread). Decide first, buy once. Fit comes before cutting so the good fabric is never the test.

## How to use

1. **New** creates a project. Numbers auto-increment (#0001). Edit to match your own (e.g. #0009).
2. Work left to right along the tape. Green top edge = gate cleared. Dimmed = previous gate still open (you can still view it).
3. **Prep:** fill the reference sheet. Decide embellishment here, not mid-sew.
4. **Source:** read the shopping list, tick items as they arrive.
5. **Sew:** add operations in order, tick as you go. Log blockers as they happen (problem, fix, lesson).
6. **Review:** keep it under 5 minutes. Three fields only.
7. **Print** (Prep or Source) outputs the reference sheet plus shopping list on one page.

## Pattern memory

When a new project's **Pattern** field matches an earlier one (same text, case ignored), that project's "change next time" note appears at the top of Prep. Type the pattern name the same way each time.

## Calendar

One date per stage plus a target finish date. A stage date turns "overdue" if it passes before the stage is done. No time blocking.

## Data

| Item | Detail |
|---|---|
| Storage | Browser localStorage, this browser and device only |
| Sync | None |
| Clearing site data | Deletes all projects |
| Backup | None built in |

## Known limits

- Gates are soft: locked stages can still be viewed.
- Pattern matching is exact text, not fuzzy.
- Shopping list is built from fabric, needle, thread and the extras box. It doesn't calculate yardage.
- Changing the stage order later will shift saved tick states.

## Ideas for later

- Export / import projects as JSON (backup, device transfer)
- Yardage calculator
- Link to fabric and pattern stash
- Photo attachments for sketch / swatch
