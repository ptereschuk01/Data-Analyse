# CRISP-DM Data Analysis Framework (EN / DE / RU)

| English | Deutsch | Русский |
|---|---|---|
| **0. Business Context and Constraints** | **0. Kontext und Einschränkungen (Business Context)** | **0. Контекст и ограничения (Business Context)** |
| **0.1 Business context and domain description** | **0.1 Beschreibung des Geschäftskontexts und der Fachdomäne** | **0.1 Описание бизнес-контекста и предметной области** |
| Industry: [e.g., telecom, retail, manufacturing] | Branche: [z. B. Telekommunikation, Einzelhandel, Produktion] | Область: [например, телеком, розница, производство] |
| Short context: business problem, current situation, why analysis is important | Kurzer Kontext: Geschäftsproblem, aktuelle Situation, warum Analyse wichtig ist | Краткий контекст: проблема бизнеса, текущая ситуация, почему анализ важен |
| Example: “Reduce customer churn in postpaid segment” | Beispiel: „Reduzierung der Kundenabwanderung im Postpaid-Segment“ | Пример: «Снижение оттока клиентов в постоплатном сегменте» |

| English | Deutsch | Русский |
|---|---|---|
| **0.2 Stakeholders and end users** | **0.2 Stakeholders und Endnutzer** | **0.2 Заинтересованные стороны и пользователи** |
| Key stakeholders: management, marketing, sales, support | Haupt-Stakeholder: Management, Marketing, Vertrieb, Support | Основные стейкхолдеры: менеджмент, маркетинг, продажи |
| End users: teams using results (CRM, dashboards, BI tools) | Endnutzer: Teams (CRM, Dashboards, BI-Tools) | Пользователи: команды, работающие с результатами |

| English | Deutsch | Русский |
|---|---|---|
| **0.3 Business KPIs** | **0.3 Geschäftskennzahlen (KPI)** | **0.3 Бизнес-метрики (KPI)** |
| KPIs to measure success | KPIs zur Erfolgsmessung | KPI для оценки результата |
| Main: Churn Rate, Retention Rate, ARPU | Haupt: Churn Rate, Retention Rate, ARPU | Основные: Churn Rate, Retention Rate, ARPU |
| Additional: ROI, revenue per user, satisfaction | Zusatz: ROI, Umsatz pro Kunde, Zufriedenheit | Дополнительные: ROI, доход, удовлетворённость |

| English | Deutsch | Русский |
|---|---|---|
| **0.4 Constraints and assumptions** | **0.4 Einschränkungen und Annahmen** | **0.4 Ограничения и допущения** |
| Data: quality, completeness, delays | Daten: Qualität, Vollständigkeit, Verzögerungen | Данные: качество, полнота, задержки |
| Resources: time, team, computing power | Ressourcen: Zeit, Team, Rechenleistung | Ресурсы: время, команда, мощности |
| Model: interpretability, reproducibility | Modell: Interpretierbarkeit, Reproduzierbarkeit | Модель: интерпретируемость |
| Legal: GDPR, bias avoidance | Rechtlich: DSGVO, Bias vermeiden | Юридические: GDPR, bias |

---

## 1. Business Understanding

| English | Deutsch | Русский |
|---|---|---|
| **1.1 Objectives** | **1.1 Ziele** | **1.1 Цели анализа** |
| **1.1.1 Business problem** | **1.1.1 Geschäftsproblem** | **1.1.1 Бизнес-проблема** |
| Identify high-risk churn customers | Kunden mit Abwanderungsrisiko identifizieren | Найти клиентов с риском оттока |

| English | Deutsch | Русский |
|---|---|---|
| **1.1.2 Success criteria** | **1.1.2 Erfolgskriterium** | **1.1.2 Критерий успеха** |
| Reduce churn by X% in Y months | Churn um X % senken | Снижение оттока на X% |

| English | Deutsch | Русский |
|---|---|---|
| **1.2 Key questions** | **1.2 Analysefragen** | **1.2 Вопросы анализа** |
| What factors influence churn? | Welche Faktoren beeinflussen Abwanderung? | Какие факторы влияют на отток? |
| Can behavior be predicted? | Verhalten vorhersagbar? | Можно ли прогнозировать поведение? |

| English | Deutsch | Русский |
|---|---|---|
| **1.3 Decisions and actions** | **1.3 Maßnahmen** | **1.3 Решения** |
| Retention campaigns | Retention-Kampagnen | Retention-кампании |
| Personalized offers | Personalisierte Angebote | Персональные предложения |
| Use in CRM / BI | Nutzung in CRM/BI | Использование в CRM |





# Checklist data mining

## 0. Context and Constraints (Business Context)

0.1 Description of the Business Context and Domain  
Industry: [specify the industry, e.g., telecommunications, retail, manufacturing].  
Brief context: business problem/task, current situation, why the analysis is important.  
Example: “The goal of the project is to reduce customer churn in the postpaid contract segment”.  

0.2 Stakeholders and End Users of the Results  
Main stakeholders: department heads, management, marketing, sales/customer service.  
End users: teams that make decisions based on the analysis results (CRM, dashboard, BI tools).  

0.3 Business Metrics (KPI)  
KPIs by which the impact of the analysis is evaluated:  
Main metrics: [e.g., Churn Rate, Retention Rate, ARPU]  
Additional metrics: campaign ROI, average revenue per customer, customer satisfaction  

0.4 Constraints and Assumptions  
Data: quality, completeness, volume, update delays  
Time and resources: project deadlines, available team, computing capacity  
Model: requirements for interpretability, reproducibility, explainability  
Legal and ethical aspects: GDPR compliance, protection of personal data, avoidance of bias  

## 1. Problem Definition (Business Understanding)  

### 1.1 Objectives of the Analysis  

1.1.1 Business Problem  
What needs to be solved: [e.g., identification of customers with high churn risk]  

1.1.2 Success Criteria  
How the result is measured: reduction of Churn Rate by X% within Y months, increase in Retention Rate, increase in ROI of retention campaigns.  

### 1.2 Key Analytical Questions  

1.2.1 Main Questions  
Which factors influence [churn, revenue, productivity]?  
Is it possible to predict the behavior of customers or employees?  

1.2.2 Hypotheses to Be Tested (priority / if possible)  
Customers with frequent support requests churn more often  
Behavioral changes (usage volume, purchases) signal risk  
Additional project-specific business hypotheses  

### 1.3 Decisions and Management Actions Based on the Analysis  

1.3.1 Possible Actions  
Targeted retention campaigns  
Personalized offers  
Optimization of service or sales processes  

1.3.2 Use of Results  
The results are integrated into business processes via CRM, BI tools, or dashboards  
Who uses them: marketing, management, customer support  
The results are regularly monitored and evaluated based on KPIs  

## 2. Data Collection (Data Understanding)  

### 2.1 Data Sources  

2.1.1 Internal Databases  
SQL (Oracle, PostgreSQL, MySQL)  
NoSQL (MongoDB, Cassandra)  

2.1.2 File-Based Sources  
CSV, Excel, Parquet  

2.1.3 API  
Internal services, external REST/SOAP APIs  

2.1.4 Web Scraping  
Websites, portals, open sources  

2.1.5 External Sources  
Open Data, Kaggle, government data, partner data  

🔹 Recommendation: Always document the retrieval date and the source version.  

### 2.2 Data Acquisition and Documentation  
Loading data from all defined sources  

Documentation of the data structure:  
table and field names, data types  
sources and retrieval date  
example values  

Documentation of all transformations (ETL processes)  

### 2.3 Relevance and Sufficiency Check  
Do the data correspond to the analysis objectives?  
Is the volume and depth sufficient for modeling or statistical analysis?  
Are there additional features that can be collected or generated (feature engineering)?  

### 2.4 Data Quality Check  
Completeness: missing values, empty fields, NA  
Plausibility of value ranges: dates, numerical indicators, categories  
Consistency between sources: matching keys, formats, duplicates  
Timeliness: data freshness, update date  
Additionally: identification of anomalies, outliers, logical integrity  

🔹 Recommendation: Document all checks in a table or a Data Quality Report to present them to stakeholders.  

## 3. Data Preparation  

### 3.1 Data Loading and Initial Review  

3.1.0 Environment Setup  
Python, Pandas, NumPy, Scikit-learn and other libraries.  
Connection to storage locations: Google Drive, local files, databases.  

3.1.1 Importing Libraries and Loading Data  
pd.read_csv, pd.read_excel, SQL queries or API.  
Verification of successful import, number of rows/columns.  

3.1.2 Initial Data Overview (Exploratory Check)  
Table dimensions, data types, sample records.  
Basic statistics: mean, median, std, min/max, quantiles.  
Immediately visible issues: missing values, duplicates, outliers.  

### 3.2 Data Cleaning / Preprocessing  

3.2.1 Handling Missing Values  
Removal of rows or columns with critical missing values.  
Imputation: mean, median, mode, “Unknown”, 0, etc.  
Documentation of the chosen strategy.  

3.2.2 Removal of Duplicates and Non-Informative Features  

3.2.2.1 Technical Identifiers  
ID, UUID, ticket numbers, indices  

3.2.2.2 Features with Zero or Near-Zero Variance  
Identical values in all rows  

3.2.2.3 Redundant Features  
Derived from each other (e.g., date and year)  

3.2.2.4 Columns with Identical Values  
E.g., column “Gender” if all entries are “Male”  

3.2.3 Treatment of Outliers  
Cause analysis: error, rare case, real extreme value  
Removal or transformation (logarithm, winsorization)  

3.2.4 Exclusion of Clearly Non-Informative Data  
Features without influence on the target variable: random codes, indices, technical fields  

### 3.3 Data Transformation (Feature Engineering / Transformation)  

3.3.0 Definition of the Target Variable  
What is predicted and at what point in time.  

3.3.1 Conversion of Data Types  
Dates → datetime  
Categories → category  
Numeric → float/int if necessary  

3.3.2 Separation of Features by Type  
Quantitative: age, price, income, number of purchases  
Qualitative: color, gender, city, car brand, payment method  
Binary: 1/0, Yes/No  

3.3.3 Quantitative Features  
Keep as is or standardize (StandardScaler) / normalize (MinMaxScaler)  

3.3.4 Encoding of Categorical Features  
Ordinal Encoding: if there is a natural order (“bad”, “average”, “good”)  
One-Hot Encoding: if order is not relevant  
Label Encoding: if there are few categories and numerical interpretation is acceptable  

3.3.5 Creation of New Features (Feature Engineering)  
Aggregations (mean, sum, max/min)  
Ratios  
Time features (year, month, day of week, season)  
Domain-specific features (e.g., “number of purchases in the last 30 days”)  

3.3.6 Data Leakage Check  
Exclusion of features containing future information or directly dependent on the target variable  

🔹 Additional Recommendations:  
1. Document all steps — especially for missing values, duplicates, and encoding.  
2. Visual data control — hist, boxplot, value_counts for categories.  
3. Logical plausibility check — e.g., age > 0, purchase date ≤ today.  
4. Save intermediate versions after each preprocessing step.  

## 4. Exploratory Data Analysis (Exploratory Data Analysis, EDA)  

### 4.1 Descriptive Statistics  
Calculation of key metrics for all quantitative features:  
Mean (mean)  
Median (median)  
Standard deviation (std)  
Minimum/maximum (min/max)  
Quartiles/percentiles (25%, 50%, 75%)  

### 4.2 Distribution Analysis  
Checking normality and feature distributions  
Determination of skewness and kurtosis  
Identification of anomalies and outliers  

### 4.3 Data Visualization  
Histograms – for distributions of quantitative features  
Boxplot – for identification of outliers  
Scatter plots – for analyzing the relationship between two quantitative features  
Heatmap – for visualization of correlations  
Bar chart – for categorical features  

### 4.4 Correlation Analysis  
Checking linear relationships between quantitative features  
For categorical features – chi2 or Cramér's V  
Identification of multicollinearity for modeling   

### 4.5 Segmentation and Hypothesis Testing  
Dividing the data into groups by key features (e.g., Pclass, gender, age groups)  
Hypothesis testing using statistical methods:  
t-test, ANOVA – for quantitative features  
chi2 – for categorical features  

🔹 Additionally:  
1. Document all charts and statistical results in the report/notebook  
2. Record conclusions in Markdown: which features are important, which outliers should be removed, which hypotheses are confirmed  
3. EDA forms the basis for feature engineering and model selection  
