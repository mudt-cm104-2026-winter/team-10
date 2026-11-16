# Team project

<!-- Replace the title with your project name. -->

## What this is

A quiz about Albania and Kosovo. Players need to answer multiple-choice questions about history, geography and culture. The app saves each player's name and score and shows a high score list, sorted from best to worst.

## How to run it

You need Python 3.10 or newer.

```bash
python3 -m venv .venv
source .venv/bin/activate          # Windows: .venv\Scripts\activate
pip install -r requirements.txt
uvicorn app.main:app --reload
```

Then open http://127.0.0.1:8000 in your browser. Stop it with `Ctrl+C`.

The entries are kept in memory: after a restart the list is empty again.

## Team
GitHub         Role
1rza           Quiz questions
ai8-tp         Quiz Page
tea-7          Docs

<!-- One row per person: GitHub username and what you mainly take care of.
No real names: this repository is public. -->

| GitHub | Role |
|---|---|

## How we work

<!-- How your team uses Git. For example:
- one branch per issue, named after it: `12-add-glossary`
- every pull request needs one approval from another team member
- the author merges after the approval
- every pull request adds a line to CHANGELOG.md
-->

## Sources

<!-- One entry per source, added on the day you use it:
- 2026-11-05: <title or link>, used for <what>
-->

## Use of AI

2026-11-16: Claude (Anthropic), used for help with solving the merge conflict on the laptop. Checked against todays-lab.md and ten-steps-to-stage-1.md.
