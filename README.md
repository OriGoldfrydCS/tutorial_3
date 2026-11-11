# tutorial_3 · Pull requests, CI and your first agent

Practice repository for TA session 3 of *AI Fluency and Agentic Methods for Engineers*
(00560413, Technion, Winter 2026-27). **Fork it**, then follow the slides.

`cooling.py` answers one question: how many minutes until a hot drink cools to
60 C, a temperature you can drink? (Newton's law of cooling.)

    python3 cooling.py              # 85 C -> 60 C: 11.23 min
    python3 cooling.py --start 88   # your own coffee
    python3 -m pytest               # the tests

Two branches, like at a company: `main` is stable and changes only through a pull
request; `develop` is where you work.

- `team/` — on `develop`, fill in `team/student.txt`, open a pull request `develop` → `main`, and let CI check your number.
- `extras/skills/team-check/` — a skill for GitHub Copilot (Part 3).
- `extras/hooks/` — an example hook. Not switched on.
- `AGENTS.md` — the rules every agent reads.
