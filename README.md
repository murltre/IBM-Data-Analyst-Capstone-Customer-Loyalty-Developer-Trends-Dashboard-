
## IBM Data Analyst Capstone — Customer Loyalty & Developer Trends

End-to-end analytics project covering data sourcing (web/API), wrangling, EDA, and interactive dashboards that surface customer satisfaction drivers and global developer tech trends. Built with Python for analysis and IBM Cognos / Looker Studio for BI storytelling.

## 📊 Datasets

CustomerLoyaltyProgram.csv and survey_data.csv (cleaned & analyzed).

Data collected via web scraping and APIs; consolidated to Pandas DataFrames for analysis.

Duplicates removed: 2,893; missing values imputed; numeric fields normalized.

(Your note: raw survey volume ≈ 64K+ rows.)

## 🛠️ Tools & Stack

Python: Pandas, NumPy, Matplotlib, Seaborn (EDA & stats)

Acquisition: requests, BeautifulSoup (API & scraping)

BI/Dashboards: IBM Cognos Analytics, Google Looker Studio

## 🔍 Methodology (E2E)

Acquire data (API + scraping) → compile to DataFrame.

Wrangle: de-dup, impute missing, normalize numerics; define duplicates by all cols and by critical cols.

EDA: distributions, outliers, correlations; focus on Country, YearsCodePro, CompTotal_normalized.

Dashboards: interactive views for Current Tech, Future Trends, Demographics (Cognos), plus a Sales view (Looker Studio).

## 📈 Dashboards (Highlights)

Current Tech Usage (Cognos)

Most-used langs: C#, HTML/CSS/JS, with SQL/TypeScript common in stacks.

Databases: PostgreSQL leads, followed by MySQL and SQL Server.

Platforms: AWS dominant; Azure second.

Frameworks: React, Spring Boot, ASP.NET Core top choices.

Future Trends (Cognos)

Languages devs want to use: Bash/Shell, HTML/CSS/JS, Python.

Databases: PostgreSQL again #1 for future work.

Platforms: AWS leads, then GCP, Azure (multi-cloud interest).

Frameworks: React, Spring Boot, Phoenix most desired.

Demographics (Cognos)

Age: 25–34 (41.3%) largest; 35–44 (27.3%) next.

Education: majority Bachelor’s (8,629) / Master’s (5,000).

Global distribution with U.S., India, Europe strongly represented.

Sales (Looker Studio)

Quantity Sold: 396.1K; Revenue: 228.7M; trends across TV & Video Gaming, Computers & Home, Smart Electronics (2016–2020).

## 💡 Key Insights

Open-source DB preference: PostgreSQL dominates current use and future interest.

Cloud platforms: AWS most used and most desired; Azure strong; GCP rising for future projects.

Frameworks: React leads both usage and interest (future preference cited at 90.1%).

Workforce profile: predominantly 25–44, highly educated, globally distributed.



