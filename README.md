\# AI-Powered Investor–Startup Matchmaking Platform

\---

\#\#\# 👥 \*\*Team Members\*\*

| Name             | GitHub Handle | Contribution                                                             |  
|------------------|---------------|--------------------------------------------------------------------------|  
| Anthony Carmona    | @AnthonyC247 | Data exploration, visualization            |  
| Bhavi Kenia   | @bhavikenia     | Data exploration, visualization, data collection, exploratory data analysis, dataset documentation  |  
| Hannah Sim     | @hanshim5  | Data exploration, visualization, model selection, hyperparameter tuning, model training, model evaluation, performance analysis, results interpretation                 |  
| Jessica Yao      | @jyao46       | Data exploration, visualization, data collection, exploratory data analysis, dataset documentation  |  
| Marcello Borromeo       | @MarcelloBorromeo    | Data exploration, visualization, model selection, hyperparameter tuning, model training, model evaluation, performance analysis, results interpretation           |
| Sanjitha Kurra       | @sanxku    | Data exploration, visualization, data collection, exploratory data analysis, dataset documentation           |

\---

\#\# 🎯 \*\*Project Highlights\*\*

\- Developed a machine learning–driven investor–startup matchmaking system to predict startup investment quality and investor fit.  
\- Trained and evaluated classification models (Logistic Regression, Random Forest, etc).
\- Achieved high AUC performance on validation and test sets, revealing strong ranking ability for investment decision support.  
\- Created a startup quality scoring system to rank both startups and venture capital firms based on historical outcomes.  

\---

\#\# 👩🏽‍💻 \*\*Setup and Installation\*\*

All work in Google Drive(not possible to combine everyone's work into one repo):
- Check "IPO Investment Analysis" folder: https://drive.google.com/drive/folders/18t-jTXR5vnDN_YV0Y9XTEYyeQy-lH7Ko?usp=sharing
- Run Colab files

\---

\#\# 🏗️ \*\*Project Overview\*\*

\- This project was completed as part of the Break Through Tech AI Program – AI Studio, in collaboration with our industry host company: International Elite Capital.
\- The objective was to build an AI-driven system that helps match startups with investors by taking in historical financial, market, and performance data. The project focuses on finding high-quality IPO candidates and ranking venture capital firms based on the long-term outcomes of the companies they back.
\- In real-world investing, decisions are often driven by pieces of data, intuition, or lack of performance. This project shows how machine learning can be used to support better investment analysis.

\---

\#\# 📊 \*\*Data Exploration\*\*

\* Structured tabular data (CSV format)
- Financial metrics (revenue, margins, valuation ratios)
- IPO pricing and aftermarket performance
- Investor and VC firm metadata

\* Data exploration and preprocessing approaches
- Standardized inconsistent financial fields
- Converted string-encoded numeric values to usable numeric formats
- Handled missing values using median imputation
- Explored feature distributions, correlations, and class imbalance

\* Insights from your Exploratory Data Analysis (EDA)  
- Certain values and return-based features showed strong predictions
- Data imbalance required careful metric selection (AUC, F1)
- Raw financial features benefited from normalization and transformation

\* Challenges and assumptions when working with the dataset(s)
- Inconsistent schemas across data sources
- Sparse data for early-stage companies
- Noisy real-world financial data

\---

\#\# 🧠 \*\*Model Development\*\*
- Models Used: Logistic Regression, random Forest, neural Network, XGBoost, decision Trees
- Feature Engineering: Financial ratios, IPO pricing and return metrics, growth indicators, and profitability measures
- Training Setup: Train/validation/test split, hyperparameter tuning using grid search, evaluation metrics(accuracy, precision, recall, F1, AUC)
- Selection: Random Forest selected for stronger nonlinear modeling and better AUC
  
\---

\#\# 📈 \*\*Results & Key Findings\*\*
<img width="778" height="368" alt="image" src="https://github.com/user-attachments/assets/1a11cc61-6386-44dd-a405-bbdc035aaeef" />

\*\*Videos\*\*

https://docs.google.com/presentation/d/1kbM60DNClpus9FfKLqPdZLbyvY0BDTag/edit?usp=sharing&ouid=112813057492552252330&rtpof=true&sd=true 

\---

\#\# 🚀 \*\*Next Steps\*\*

- Address class imbalance with additional sampling strategies
- Incorporate time-series financial trends instead of static snapshots
- Expand dataset to include private funding rounds
- Add fairness and bias evaluation across industries and company sizes
- Deploy as an interactive dashboard for investors
