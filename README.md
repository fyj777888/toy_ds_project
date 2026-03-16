# toy_ds_project
The first dsci project  
"project creation date:2026.2.2"  
"author:Ethan Fan"

## Overview

This project explores a classic example of a **spurious correlation** — a statistical relationship between two variables that have no meaningful causal connection.

Specifically, it visualizes the surprisingly high correlation between:
- 🧈 **Per capita margarine consumption** in the United States (lbs/year)
- 💔 **Divorce rate in Maine** (per 1,000 people)

Data is sourced from Tyler Vigen's [Spurious Correlations](http://www.tylervigen.com/spurious-correlations) website, covering the years 2000–2009.

## Key Message

> **Correlation does not imply causation.**

Just because two variables move together does not mean one causes the other. This example is a lighthearted reminder to think critically when interpreting statistical relationships.

## Contents

| File | Description |
|------|-------------|
| `marg_vs_divorce_viz.ipynb.ipynb` | R notebook with data wrangling and visualization code |

## Requirements

The notebook uses the following R packages:
- [`tidyverse`](https://www.tidyverse.org/) — data manipulation and plotting
- [`cowplot`](https://wilkelab.org/cowplot/) — combining multiple plots
- [`scales`](https://scales.r-lib.org/) — axis label formatting
