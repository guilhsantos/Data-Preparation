[🇧🇷 Português](README.md) · 🇺🇸 **English**

# Data preparation for modeling

A Python pipeline that cleans, enriches, and combines three datasets (projects, campaigns, and backers) into a single table ready for predictive models.

[![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/guilhsantos/Data-Preparation/blob/main/DataPreparationPratica.ipynb)

## Problem

Project, campaign, and investment data lived in three separate files with inconsistent types, unused columns, and missing values. No model can be trained on that.

## Solution

A notebook that loads `DataPrepFinal.csv`, `campaign.csv`, and `invested.csv`, standardizes each one, and merges them into a single consistent dataset.

## Result

A single clean dataset with correct types, no intermediate columns, and new features such as each project's duration (`time_range`).

## How I did it

1. **Cleaning:** removed irrelevant columns, fixed types, and handled nulls.
2. **Enrichment:** created derived features such as `time_range`.
3. **Integration:** merged campaigns and backers into the projects table.
4. **Final adjustments:** removed intermediate columns and checked consistency.

Built during the Data Preparation class of the DNC Data Scientist program.

## Stack

Python · pandas · Google Colab

---

Made by [Guilherme Santos](https://portifolio-guilherme-santos.vercel.app) · [LinkedIn](https://www.linkedin.com/in/guilherme-santos-dataeng)
