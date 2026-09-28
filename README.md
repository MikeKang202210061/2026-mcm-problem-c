# Dance Competition Vote Modeling

An organized, reproducible portfolio of our solution to Problem C of the 2026 Mathematical Contest in Modeling (MCM). The team received an Honorable Mention.

This portfolio title is descriptive; the work remains identified below as the team's 2026 MCM Problem C submission.

## Problem

The project analyzes the scoring and elimination mechanisms of *Dancing with the Stars*. Because public vote totals are latent, we developed models to infer feasible fan support, compare historical scoring systems, identify factors associated with competitive success, and propose a fairer mechanism.

## Methods

- Data cleaning, normalization, and exploratory analysis across 32 seasons
- Latent fan-vote estimation under multiple scoring rules
- Consistency and robustness testing against observed eliminations
- Dual-track OLS regression for judge and fan effects
- Choquet-integral mechanism design
- Multi-objective optimization and Pareto-frontier analysis
- Sensitivity analysis and visual validation

## Repository structure

```text
paper/       Final team report
problem/     Official problem statement
data/raw/    Official source dataset
data/processed/  Core cleaned and unified datasets
notebooks/   Data/modeling and optimization workflows
figures/     Selected report-ready visualizations
```

Notebook outputs were cleared to keep the repository compact. Run the notebooks in numerical order from the repository root.

## My contribution

I researched candidate algorithms and their mathematical foundations, helped translate the theory into an implementable workflow, and produced analytical visualizations used to interpret and communicate the results.

## Environment

```bash
python -m venv .venv
pip install -r requirements.txt
jupyter lab
```

## Team attribution

This was a collaborative MCM submission by Team 2617626. The repository is published as a portfolio record of the team's work; the final report represents the joint submission.
