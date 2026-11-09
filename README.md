# Analyzing LLMs with Surveys

See [PROSJEKTBESKRIVELSE.md](PROSJEKTBESKRIVELSE.md) for a Norwegian summary of UiO’s project description. This README describes the repository setup and a suggested workflow.

## 1. Purpose of This Repository

This repository brings together code, experiment configurations, literature notes, and thesis writing. The following structure is intended to keep the project organized. This will make it easier to trace future analyses back to the data, code and settings used- 

## 2. Repository Structure

```text
llm-survey-analysis/
├── README.md                    Project overview and setup
├── PROSJEKTBESKRIVELSE.md        Summary of the UiO project
├── configs/
│   └── pilot.json               Configuration for the dry run
├── data/
│   ├── README.md                Dataset documentation
│   ├── examples/                Synthetic example questions
│   ├── raw/                     Local placeholder for raw data
│   └── processed/               Locally processed data
├── docs/
│   ├── project-plan.md          Preliminary project plan
│   ├── literature.csv           Research literature overview
│   ├── research-log.md          Work log and project decisions
│   └── experiment-template.md   Template for planning experiments
├── prompts/                     Instructions for language models
├── src/
│   └── run_pilot.py             Local dry-run implementation
├── tests/
│   └── test_run_pilot.py        Automated tests
├── notebooks/                   Exploratory analysis
├── results/
│   ├── runs/                    Local run outputs
│   └── figures/                 Reviewed figures for sharing
├── writing/
│   └── outline.md               Preliminary thesis outline
├── .env.example                 Empty template for a future API key
├── .gitignore                   Rules for excluding files from Git
└── requirements.txt             Python dependency information
```
Documentation date: November 9, 2026.
