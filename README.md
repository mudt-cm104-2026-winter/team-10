# Albania & Kosovo Quiz


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

The quiz scores are kept in memory: after restarting the app, the high score list will be empty again.

## Team

| GitHub | Role |
|---|---|
| 1rza | Quiz questions |
| ai8-tp | Quiz page |
| tea-7 | Documentation |

## How we work

- We create a GitHub issue for each task and attach it to one of our three epics.
- Each task is completed on a separate branch linked to its issue.
- We open pull requests describing what changed and why, using `Closes #n` to link the issue.
- Another team member reviews the changes and leaves comments on specific lines of code when appropriate.
- Pull requests require at least one approval before being merged into `main`.
- We use our GitHub project board to track tasks as Todo, In progress, and Done.

## Sources

- 2026-11-16: `assessment-1-team-project.md`, used to check the Assessment 1 requirements.
- 2026-11-16: `ten-steps-to-stage-1.md`, used to check the GitHub workflow and submission checklist.

## Use of AI

2026-11-16: Claude (Anthropic), used for help with solving the merge conflict on the laptop. Checked against todays-lab.md and ten-steps-to-stage-1.md.
- 2026-11-16: ChatGPT (OpenAI), used for guidance on Git commands, creating issues and pull requests, and updating the README. Checked by comparing the instructions with the course assessment checklist and verifying changes in VS Code and GitHub.
- 2026-11-16: ChatGPT (OpenAI), used for suggestions on adapting the original HTML homepage into an Albania and Kosovo quiz introduction. Checked by reviewing the HTML changes in VS Code and the pull request diff on GitHub.
- 2026-11-17: ChatGPT (Open AI), used to help write the changelog entry (PR #18). Checked by reading it and comparing with the course checklist.
