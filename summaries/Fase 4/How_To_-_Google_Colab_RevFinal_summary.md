# How To - Google Colab RevFinal.pdf

**File type:** PDF | **Processed:** 2026-04-22

## TL;DR
A beginner’s roadmap for ditching "Blue Screen" Excel crashes by moving data analysis into Google Colab.

## What's Inside
* **Excel to CSV Workflow:** Steps to convert `.xlsx` to `.csv` with specific reminders to verify semicolons and decimals in Notepad.
* **Colab Hotkeys:** Essential shortcuts including `Ctrl+M+B` for code blocks, `Ctrl+M+M` for text, and `Ctrl+M+D` to delete.
* **Data Ingestion:** How to use the side-panel upload and the specific `pd.read_csv` parameters (`sep=';'`, `encoding='latin1'`, `decimal=','`) required for local data.
* **Analysis Snippets:** Core Python modules (`numpy`, `pandas`) and the `dados.head()` function for initial data previews.
* **Output Management:** Instructions for renaming notebooks and downloading results for local storage.

## Worth Knowing
This guide is specifically tailored for users facing hardware limitations; it frames Colab as the solution to Excel's inability to handle massive datasets without freezing your OS. Keep an eye on the CSV separator—the code assumes a semicolon (`;`), which is common in European/LatAm Excel exports but different from the standard US comma.
