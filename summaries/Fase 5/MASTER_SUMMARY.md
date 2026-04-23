# File Processing Report

**Source folder:** `Fase 5`  
**Processed:** 2026-04-23  
**Files analysed:** 24

---

## 07 - STO - Validando a solucao_RevFinal.pdf `PDF`

## TL;DR
A guide to validating startup ideas using Lean methodology and specific MVP types to avoid the "Alice in Wonderland" trap of building things nobody wants.

## What's Inside
- **Build-Measure-Learn Cycle:** The core loop for turning ideas into data and deciding whether to pivot (change strategy) or persevere.
- **The MVP Toolkit:** Practical breakdowns of **Concierge** (manual service), **Wizard of Oz** (manual backend, automated front), **Smoke Tests** (landing pages), and **Crowdfunding**.
- **Earlyevangelists:** How to identify the obsessive early adopters who will buy a visionary product even if it's "minimum" or buggy.
- **The Trinity:** A clear distinction between **PoC** (is it possible?), **Prototype** (how does it look/work?), and **MVP** (will they pay for it?).
- **Case Studies:** Quick snapshots of how Uber, Dropbox, Zappos, and AirBnB validated their concepts before scaling.

## Worth Knowing
The document highlights that "Minimum" isn't the goal—the goal is the shortest path through the feedback loop. If you aren't talking to customers "in the street" (Steve Blank style), you're just guessing.

---

## 2TSCOR Challenge MaterDei 2oSem 2025 v2 RevFinal.pdf `PDF`

## TL;DR
Project brief for the 2025/2026 FIAP Data Science challenge to boost MaterDei’s patient appointment conversion rates.

## What's Inside
- **The Goal:** Use anonymized healthcare data to predict and improve how many patients actually show up for exams and consultations.
- **Group Specs:** Teams of up to 5; no member swaps allowed after Sprint 3; all members must keep local copies of all files.
- **The Workflow:** 4 distinct Sprints ending with a final report and a YouTube pitch link (sent via .txt file).
- **Success Factors:** Mandatory report and pitch; high-value "extras" include Power BI/Python dashboards and real-time predictive models.
- **The Reward:** Top 3 groups present at NEXT 2026 for prizes like cash vouchers and medals.

## Worth Knowing
MaterDei provides sample data, but the "secret sauce" is finding reliable public datasets to augment your analysis. Also, ensure all filenames and RMs are listed in alphabetical order—the instructors use this specifically for grading efficiency.

---

## Cap 01 - EXPLORANDO RECURSOS ANALÍTICOS COM DATA VIZ E DATA SCIENCE RevFinal (1).pdf `PDF`

## TL;DR
Project brief for "Melhores Compras" detailing three analytical challenges—Data Viz, Data Exploration, and Linear Regression—using 5 years of pet shop sales data.

## Numbers & Dates
- **2020–2024:** The timeframe for the sales data provided.
- **~250,000:** Total rows in the primary CSV file (`vendas_linha_petshop`).
- **3 Deliverables:** A strategic dashboard, an exploratory data analysis, and a marketing-focused regression model.

## What This Means
This document moves the company from simple storage to a data-driven culture. You aren't just making charts; you're using Python and Power BI to explain consumer behavior and predict the impact of advertising spend. The data is messy because it's been handled manually across different departments, so prep work is mandatory.

## Next Move
- **Scrub the CSV:** The prompt explicitly warns that the sales data has manual errors and needs cleaning before you touch a dashboard.
- **Alphabetize your team:** The final delivery requires a `componentes.txt` file with members in alphabetical order—don't lose points on the easy stuff.

---

## Cap 01 - EXPLORANDO RECURSOS ANALÍTICOS COM DATA VIZ E DATA SCIENCE RevFinal.pdf `PDF`

## TL;DR
A three-part analytical roadmap for the Melhores Compras digital transformation, covering strategic dashboards, exploratory data science, and predictive marketing models.

## Numbers & Dates
- **2020–2024**: Timeframe for the 250k-line sales dataset.
- **50,000+**: Total SKUs available in the catalog.
- **3 Challenges**: DataViz (PowerBI/Tableau), Exploratory Science (Python), and Linear Regression (Marketing spend).

## What This Means
Jobs is pushing for a full "data-driven" culture rather than just storing records. We’re moving from basic reports to using a 5-year sales history to explain customer behavior and applying regression to see how marketing spend actually impacts the bottom line. It's about turning "gut feelings" into predictive models that the commercial team can actually use for their monthly meetings.

## Next Move
Prioritize cleaning the `vendas_linha_petshop_2024.csv` file first; the brief specifically warns it has manual errors and inconsistencies from being passed between departments.

---

## Cap 02 - Métodos e Conceitos de Visualização de Dados RevFinal.pdf `PDF`

## TL;DR
A foundational guide to Data Viz concepts, mapping the transition from a VUCA to a BANI world and detailing the essential toolkit for modern data storytelling.

## What's Inside
- **The BANI Framework:** Why we need visuals to navigate a world that is Brittle, Anxiety-inducing, Non-linear, and Incomprehensible.
- **Market Leaders:** A breakdown of the Gartner Magic Quadrant featuring Power BI, Tableau, Qlik, and SAP.
- **Core Applications:** Strategies for spotting trends, identifying outliers (like COVID-19 death spikes), and communicating specific points of view.
- **Visual Toolkit:** Definitions and use cases for Histograms, Candlestick charts, Ishikawa diagrams, Heat Maps, and Infographics.
- **Self-Service BI:** A look at how the industry is moving toward "drag-and-drop" autonomy for non-technical users.

## Worth Knowing
The transition to BANI means data is no longer just "complex"—it's often incomprehensible, making visual synthesis a survival skill for decision-makers rather than just a "nice-to-have" report feature. It highlights that the human element is still the final filter for interpretation, no matter how good the dashboard is.

---

## Cap 03 - Técnicas de Visualização RevFinal.pdf `PDF`

## TL;DR
A strategic guide for choosing the right chart type based on your goal—whether you're comparing categories, tracking trends, or avoiding common visual traps.

## What's Inside
* **Comparison Tools:** Bar charts are the "Swiss Army knife" here; use Heat Maps when dealing with dense tables where numbers look too similar.
* **Trend Tracking:** Line charts for time-series data and Area charts for showing how the "part-to-whole" relationship evolves over time.
* **The Pie Chart "Fix":** Strict rules to keep them readable—never exceed 6 slices, group tiny categories into "Others," and absolutely no 3D effects.
* **Geospatial Viz:** Techniques for overlaying bubbles and pies on maps to show regional distributions and trends.

## Worth Knowing
The guide emphasizes that 3D projections are a major "don't" because they distort proportions, making smaller percentages look larger than they are. If you're stuck, the bar chart is your safest bet for almost any comparison.

---

## Cap 04 - Tipos, estilos e usos de gráficos RevFinal.pdf `PDF`

## TL;DR
A cheat sheet for picking the right chart type based on whether you're showing comparisons, distributions, compositions, or relationships.

## What's Inside
- **Selection Matrix:** A decision tree (Figure 1) to help you choose the correct visual based on your data goals.
- **Core Visuals:** Deep dives into Line (temporal), Bar (categorical), Stacked Bar (parts-to-whole), and Scatter (correlation) charts.
- **Specialized Formats:** Use cases for Histograms, Candlesticks for market trends, and Treemaps for hierarchical data.
- **Analysis Tools:** How to use Heatmaps for dense tables and Fishbone (Ishikawa) diagrams for root cause mapping.
- **Data Literacy Basics:** Concepts of Gestalt and neurobiology applied to how we perceive images and symbols.

## Worth Knowing
This guide emphasizes "Visual Literacy"—the idea that great charts don't just show data, they leverage brain shortcuts (Gestalt principles) to make insights instant and obvious. If you're stuck on how to visualize a complex correlation, check the Scatter and Bubble chart sections (2.2.6 - 2.2.7).

---

## Cap 05 - Gráficos combinados, bubble charts, pareto e waterfall RevFinal.pdf `PDF`

## TL;DR
A tactical guide to using specialized charts—Combined, Bubble, Pareto, and Waterfall—to turn complex data into clear business narratives.

## What's Inside
- **Dual-Axis Strategies:** How to mix bars and lines (e.g., revenue vs. profit margin) without confusing the viewer.
- **Bubble Chart Variables:** Using X/Y position, size, and color to map four different dimensions like market share and annual growth.
- **Pareto (80/20) Logic:** Step-by-step on isolating the "vital few" causes (the 20%) that drive 80% of your problems or results.
- **Waterfall Mechanics:** Visualizing cumulative flow, specifically for financial cash movement or HR headcount changes.
- **Unusual Combos:** Tips on layering area charts with lines to highlight "total time" in complex workflows.

## Worth Knowing
The guide highlights a clever Knaflic technique: using a combined area/line chart for insurance claims to emphasize the total wait time for the customer rather than just individual processing steps. It’s a great way to prioritize the "human" impact of data.

---

## Cap 06 - Técnicas de Desenho de Painéis RevFinal.pdf `PDF`

## TL;DR
A masterclass on building dashboards that actually get used, categorized by organizational level from real-time floor ops to long-term executive strategy.

## What's Inside
*   **The Hierarchy of Needs:** Breakdown of Operational (real-time/efficiency), Tactical (departmental/analytical), and Strategic (KPIs/projections) dashboard types.
*   **Design Guidelines:** Specific rules for "sectorization" (grouping similar metrics) and visual hierarchy to prevent cognitive overload.
*   **Financial Subsets:** Focus on cash flow and budget-specific tactical panels for managers.
*   **Implementation Tactics:** Best practices for using white space, choosing color palettes, and ensuring data quality through "news-style" highlighting.

## Worth Knowing
A common pitfall flagged here is "info-dumping"—showing raw operational data to investors or executives usually kills engagement. The goal isn't to show all the data, but to answer the specific "why" or "what now" for the intended audience level.

---

## Cap 07 - Explorando o Tableau RevFinal.pdf `PDF`

## TL;DR
A foundational guide to navigating Tableau Desktop and Public, focusing on data connection, UI layout, and the crucial distinction between dimensions and measures.

## What's Inside
- **Data Connectors:** Steps for linking local files (Excel/Text), relational databases, and cloud-based Big Data sources.
- **Interface Map:** Breakdown of the Data Panel, Toolbars, Shelves (Columns/Rows), and the Workspace (Sheets, Dashboards, Stories).
- **Dimensions vs. Measures:** Definitions for qualitative fields (blue) vs. aggregatable numeric data (green).
- **Advanced Fields:** Quick look at creating Sets, Parameters, and Calculated Fields to manipulate raw data.
- **Tableau Public:** Details on the free version for students/teachers and building a public-facing portfolio.

## Worth Knowing
The document highlights that Tableau Public isn't just a trial—it's a massive learning repository where you can reverse-engineer visualizations from other users to level up your skills.

---

## Cap 08 - Explorando o Power BI RevFinal.pdf `PDF`

## TL;DR
A foundational guide to the Power BI ecosystem, mapping the journey from raw data import in Desktop to sharing interactive dashboards via the Cloud.

## What's Inside
- **Core Triad:** Power BI Desktop (for building), Power BI Service (for publishing), and Mobile Apps (for consuming).
- **The Workflow:** A 4-step loop: Import/Clean $\rightarrow$ Design Report $\rightarrow$ Publish to Service $\rightarrow$ Share with Stakeholders.
- **The Elements:** Clear distinctions between Visualizations, Datasets, Reports, Dashboards, and Tiles.
- **Power Query Basics:** Step-by-step on connecting Excel sources, transforming data types, and using the "Applied Steps" history.
- **Reporting 101:** Practical tips on dragging fields, using map visuals, and formatting report pages.

## Worth Knowing
Dashboards and Reports aren't the same here—you build multi-page Reports in the Desktop app, but "Dashboards" are single-page high-level overviews created exclusively within the online Power BI Service. If you're looking for the data cleaning engine, look for the "Transform Data" button to trigger Power Query.

---

## Cap 09 - Análise e Visualização de Dados - Hands On RevFinal.pdf `PDF`

## TL;DR
A foundational guide to data visualization theory paired with a step-by-step Tableau tutorial using a pet shop dataset.

## What's Inside
- **Design Fundamentals:** Specific frameworks for clarity, simplicity, and audience adaptation (Quadro 1 & 2).
- **Chart Selection Matrix:** Direct mapping of data types—categorical, temporal, and geospatial—to their ideal visual representations.
- **Tableau Hands-on:** Practical walkthroughs for building bar charts, correlation matrices, and pie charts from scratch.
- **Tool Mechanics:** Detailed breakdowns of Tableau’s *Granularidade*, *Marcas*, and *Editar Eixo* menus.
- **Ethics Check:** Guidelines on avoiding data distortion and maintaining visual honesty during analysis.

## Worth Knowing
The tutorial section (starting page 16) is designed for literal replication; if you have the Petshop CSV, you can build the entire dashboard in about 20 minutes. Pay close attention to the "Granularidade" tips—they address the most common stumbling blocks for Tableau beginners.

---

## Cap 10 - Modelagem Preditiva RevFinal (1).pdf `PDF`

## TL;DR
A comprehensive roadmap for building, evaluating, and deploying machine learning models using the CRISP-DM framework.

## What's Inside
- **Analytics Hierarchy:** Evolution from Descriptive (what happened) to Prescriptive (what to do) and full AI automation.
- **CRISP-DM Workflow:** The 6-step lifecycle covering business understanding, data prep (feature engineering), and MLOps/Deploy.
- **Regressors vs. Classifiers:** Predicting continuous numbers (sales/forecasting) versus categorical labels (churn/fraud/image detection).
- **Python Pipelines:** Specific code snippets for wine rating datasets and basic ML model structures using `sklearn`.
- **Validation Metrics:** Math for "Loss Functions" in regression and Confusion Matrices (Accuracy, Precision, Recall) for classification.

## Worth Knowing
Models aren't exact formulas—they are statistical estimates where success is defined by whether the "error rate" is low enough for your specific business case. The process is intentionally cyclical; you'll likely iterate through hundreds of models before hitting the right balance.

---

## Cap 10 - Modelagem Preditiva RevFinal.pdf `PDF`

## TL;DR
A foundational roadmap for building and evaluating predictive models, from business logic to Python implementation.

## What's Inside
- **The Analytics Ladder:** Breaks down the evolution from Descriptive (what happened) to AI (automated action).
- **CRISP-DM Workflow:** A 6-step cycle covering business understanding, data prep (feature engineering), and deployment.
- **Regressors vs. Classifiers:** Clear distinction between predicting continuous numbers (sales forecasting) and categories (churn or fraud detection).
- **Evaluation Toolkit:** Deep dive into the Confusion Matrix, Precision, Recall, and Loss Functions for measuring error.
- **Code Snippets:** Python templates for building basic ML pipelines and calculating confidence intervals.

## Worth Knowing
Models are never "perfect" formulas; they are statistical estimates where an inherent error is always expected. The goal isn't zero error, but an "acceptable" error level for the specific business problem you're solving.

---

## Cap 11 - Regressão Linear Um dos pilares para análise de dados RevFinal.pdf `PDF`

## TL;DR
A foundational guide to Linear Regression—predicting numerical values by fitting a straight line through data points.

## What's Inside
- **Core Concepts:** Visualizing the relationship between $y$ (target/endogenous) and $x$ (predictor/exogenous) variables.
- **Error & Uncertainty:** Breakdown of residuals (the vertical distance from the line) and how to interpret confidence interval "shadows" in forecasts.
- **Python Workflows:** Specific code pipelines for `pandas` and `scikit-learn` to move from simple to multivariable models.
- **Model Health:** Statistical checks like the Pearson correlation method, p-values for significance, and simulations of overfit.

## Worth Knowing
This chapter uses Brazilian GDP (PIB) and highway traffic data (ABCR) to prove a real-world point: road movement is a highly accurate leading indicator for economic growth. The math here serves as the literal "pilar" (pillar) for almost all modern Machine Learning algorithms.

---

## Cap 12 - Árvores de Decisão RevFinal.pdf `PDF`

## TL;DR
A technical deep-dive into how decision trees and random forests use probability theory to predict outcomes like e-commerce conversions.

## What's Inside
* **Probability Fundamentals:** Differentiates between *a priori* (math-based) and empirical (experience-based) probability.
* **The "Branches" Logic:** Visual guides on how to read decision paths—e.g., how browser type plus visit count predicts purchase intent.
* **Math Axioms:** Breakdown of Bayes’ Theorem and probability rules used to calculate node splits.
* **Random Forest:** Introduction to ensemble modeling, using multiple trees to improve prediction accuracy.
* **Python Implementation:** Code snippets for loading data and generating graphical tree visualizations.

## Worth Knowing
The document emphasizes that while decision trees are great for "reading" a scenario, they rely heavily on empirical data—essentially looking at past frequency to bet on future behavior. It’s the bridge between high school statistics and modern machine learning.

---

## Cap 13 - Estimação e Discriminação RevFinal.pdf `PDF`

## TL;DR
A guide to separating data classes using Linear (LDA) and Quadratic (QDA) Discriminant Analysis in Python, focusing on the geometric differences between classifiers.

## What's Inside
- **Classifier Comparison:** Visual breakdown of why Decision Trees create "steps" while LDA/QDA produce clean lines and parabolic curves.
- **Python Workflow:** Step-by-step code for the `mtcars` dataset using `mpg` and `wt` to predict cylinder counts (`cyl`).
- **Data Prep:** Snippets for Log-Linear transformations to fix skewed distributions before running discriminants.
- **Performance Benchmarks:** A pros-and-cons table comparing accuracy across KNN, LDA, and QDA.

## Worth Knowing
Decision Trees use simple "if/then" logic that results in blocky, rectangular data splits. If your data classes aren't easily boxed in, LDA (for linear splits) or QDA (for curved, parabolic splits) usually provide a much tighter fit.

---

## Cap 14 - Análises de Séries Temporais com Python RevFinal.pdf `PDF`

## TL;DR
A step-by-step technical guide for predicting future values using Python and the classic ARIMA (Box-Jenkins) methodology.

## What's Inside
*   **Stationarity Testing:** Practical code for the Dickey-Fuller test to determine if your data's mean and variance are stable.
*   **The ARIMA Pillars:** Breakdown of how to identify orders for Autoregression (p), Integration (d), and Moving Average (q).
*   **Data Prep Snippets:** Python scripts for converting date columns, applying "first differences," and plotting ACF/PACF charts.
*   **Model Evaluation:** A workflow for splitting train/test sets and diagnosing model quality via residual error analysis.

## Worth Knowing
Standard linear regression usually fails on time series because it ignores the correlation between past and present; this guide focuses on "Integrating" the data to fix that specific bias.

---

## Cap 15 - Modelagem de dados RevFinal.pdf `PDF`

## TL;DR
A foundational guide to data modeling, covering Big Data concepts, ML lifecycles, and hands-on Python workflows with NumPy and Pandas.

## What's Inside
- **Data Archetypes:** Classifications by source, structure, and type, including the "5 V’s" of Big Data.
- **ML Pipeline Fundamentals:** Detailed breakdowns of Train/Test/Validation splits, Overfitting vs. Underfitting, and the "Ideal Model" definition.
- **NumPy Mastery:** Practical code for matrix operations, array manipulation, and performance benchmarks against standard Python lists.
- **Pandas & Scikit-learn:** 20+ code snippets covering data cleaning, handling missing values with `missingno`, and feature engineering like one-hot encoding and scaling.

## Worth Knowing
The guide places a heavy emphasis on the "Feature Engineering" phase, specifically showing how to transform nominal/ordinal categories and normalize data before it hits a model. It’s essentially a cheat sheet for the messy pre-processing stage of the Data Science lifecycle.

---

## Cap 16 - Introdução à Inteligência Artificial RevFinal.pdf `PDF`

## TL;DR
A technical deep dive into AI fundamentals, covering the theory of machine learning and hands-on Python implementation using Scikit-Learn.

## What's Inside
- **Concept Map:** Clear breakdown of AI vs. Machine Learning vs. Deep Learning and the history from Perceptrons to now.
- **Supervised Learning:** Code snippets for simple/multiple linear regression and K-Nearest Neighbors (KNN) classification.
- **Clustering Logic:** Practical guide to K-Means and using the "Elbow Method" to determine the optimal number of data groups.
- **Ethical Framework:** A critical look at algorithmic bias, specifically referencing the *Coded Bias* documentary and strategies for ethical AI.
- **Preprocessing Workflow:** Real-world Python steps for dropping useless columns, handling duplicates, and normalizing data before training.

## Worth Knowing
The guide focuses heavily on the `sklearn` library, providing a ready-to-copy pipeline that bridges the gap between raw data cleaning and a functional model. It specifically highlights that model accuracy often depends more on normalization than the algorithm choice itself.

---

## Cap 17 - Introdução às redes neurais artificiais RevFinal.pdf `PDF`

## TL;DR
A foundational guide to Artificial Neural Networks that bridges biological theory with hands-on Perceptron coding in Python.

## What's Inside
- **Neuron Anatomy:** Mapping dendrites to inputs, synapses to weights, and the cell body to summation and activation.
- **Activation Functions:** Visual breakdown of the Step (binary) and Sigmoid (probabilistic) functions.
- **Manual Training:** Step-by-step tables showing how weights adjust until a model masters the AND logic gate.
- **Python Implementation:** Practical walkthrough using `scikit-learn` to classify the classic Iris flower dataset.
- **Evaluation Metrics:** Snippets for calculating accuracy and generating confusion matrices to see where a model trips up.

## Worth Knowing
The Perceptron is the "ancestor" of modern AI; it is perfect for learning linear patterns, but it physically cannot solve non-linear problems—a limitation that led to the development of deep learning.

---

## HOW TO - Google Colab RevFinal.pdf `PDF`

## TL;DR
A beginner’s roadmap for moving heavy data analysis from crashing Excel spreadsheets to Google Colab using Python.

## What's Inside
* **The CSV Bridge:** Specific steps to export Excel files using semicolon (`;`) separators and comma (`,`) decimals for Python compatibility.
* **Essential Hotkeys:** `Ctrl+M+B` to spawn code cells and `Ctrl+M+M` for text/markdown blocks.
* **Data Ingestion:** A boilerplate code snippet using `pandas` that handles the common `latin1` encoding headache.
* **Initial Analysis:** Quick functions like `head()` for previews and `describe()` for instant statistical summaries.
* **Environment Setup:** Visual guide for uploading local files to the Colab sidebar before running scripts.

## Worth Knowing
Files uploaded directly to the Colab sidebar are temporary. If the session times out or you close the tab, you’ll have to re-upload your data—unless you mount your Google Drive for permanent storage.

---

## HOW TO - POWER BI RevFinal.pdf `PDF`

[Gemini error: 429 RESOURCE_EXHAUSTED. {'error': {'code': 429, 'message': 'You exceeded your current quota, please check your plan and billing details. For more information on this error, head to: https://ai.google.dev/gemini-api/docs/rate-limits. To monitor your current usage, head to: https://ai.dev/rate-limit. \n* Quota exceeded for metric: generativelanguage.googleapis.com/generate_content_free_tier_requests, limit: 20, model: gemini-3-flash\nPlease retry in 54.960140692s.', 'status': 'RESOURCE_EXHAUSTED', 'details': [{'@type': 'type.googleapis.com/google.rpc.Help', 'links': [{'description': 'Learn more about Gemini API quotas', 'url': 'https://ai.google.dev/gemini-api/docs/rate-limits'}]}, {'@type': 'type.googleapis.com/google.rpc.QuotaFailure', 'violations': [{'quotaMetric': 'generativelanguage.googleapis.com/generate_content_free_tier_requests', 'quotaId': 'GenerateRequestsPerDayPerProjectPerModel-FreeTier', 'quotaDimensions': {'location': 'global', 'model': 'gemini-3-flash'}, 'quotaValue': '20'}]}, {'@type': 'type.googleapis.com/google.rpc.RetryInfo', 'retryDelay': '54s'}]}}]

---

## HOW TO - Tableau RevFinal.pdf `PDF`

## TL;DR
A foundational guide to navigating the Tableau interface and connecting your first dataset.

## What's Inside
- **Quick Download:** Direct link for Tableau Public to get started for free.
- **Toolbar Cheat Sheet:** A table of icons for every core action, including "Swap Rows/Columns," "Fix Axis," and "Presentation Mode."
- **Data Icon Legend:** Deciphers the symbols for booleans, strings, dates, and geographic roles.
- **Dimensions vs. Measures:** A breakdown of how Tableau categorizes qualitative (blue) vs. quantitative (green) data.
- **Connection Hub:** Visual walk-through of linking local Excel files, SQL databases, or web sources.

## Worth Knowing
The guide highlights that students and teachers can claim a full Tableau Desktop license for free. If you're looking for inspiration, use the Tableau Public repository mentioned on page 6—it's essentially the "GitHub of data viz."

---
