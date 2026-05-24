# makeaproject

<!-- Once CI is set up (Step 7), uncomment and update OWNER/REPO:
[![CI](https://github.com/OWNER/REPO/actions/workflows/ci.yml/badge.svg)](https://github.com/OWNER/REPO/actions/workflows/ci.yml)
-->
This is a first trial of Step 3 and onward in "thebasics" teaching bootcamp. For this example, we'll play with NBA play-by-play data from 1997-2025 available at: https://www.kaggle.com/datasets/szymonjwiak/nba-play-by-play-data-1997-2023

The repo itself started with a template (https://github.com/davidelbert/project-template) and was created with a simple bash command:
```
gh repo create nba_teaching_repo --public --clone --template davidelbert/project-template
```
The repo is a deliverable for the next meeting with a collaborative group charged with learning to explore a dataset as a team.

## Quickstart

```bash
git clone git@github.com:OWNER/REPO.git
cd REPO
uv venv
uv pip install -e ".[dev]"
uv run jupyter lab
```

Then open `notebooks/01-explore.ipynb` and run all cells.

New to this repo? Read **RUNBOOK.md** for the literal step-by-step, and
**DATA.md** for where the data comes from and how to fetch it.

## Layout

```
.
├── data/                 # not in git — see DATA.md
├── notebooks/            # numbered, narrative analyses
├── scripts/              # fetch_data.py and other one-off utilities
├── src/myproject/        # reusable functions; notebooks import from here
└── tests/                # pytest tests for src/
```

## Data

See **DATA.md** for the source, citation, license, and the exact command
to fetch the raw data. Raw data is never committed to this repo.

## Findings

(Filled in as the project progresses. Step 5's last issue is to write this section.)

## Status

Pre-alpha / in progress / archived — pick one.
