# HOW TO - Google Colab RevFinal.pdf

**File type:** PDF | **Processed:** 2026-06-01

## TL;DR
A beginner’s guide to migrating from crash-prone Excel sheets to Python-powered data analysis in Google Colab.

## What's Inside
* **Excel-to-CSV Workflow:** Step-by-step instructions for converting `.xlsx` files into a Python-friendly format using the "CSV (Comma delimited)" save option.
* **Colab Keyboard Shortcuts:** Speed up your workflow with `Ctrl+M+B` (new code block), `Ctrl+M+M` (text block), and `Ctrl+M+D` (delete block).
* **Data Import Boilerplate:** Pre-written `pandas` code for loading local files, specifically handling European/Latin formatting with `sep=';'` and `decimal=','`.
* **Exploratory Basics:** Quick methods to verify your data, including `head()` for row previews and `describe()` for instant statistical summaries.

## Worth Knowing
The guide specifically flags `encoding='latin1'` and semicolon separators—essential settings to prevent your import from breaking if the original Excel file has special characters or European formatting. It’s designed as a "safety net" for when your local machine starts hitting the "blue screen of death" due to massive datasets.
