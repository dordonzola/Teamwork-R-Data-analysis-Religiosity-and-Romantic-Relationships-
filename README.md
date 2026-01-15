# Religiosity and Attitudes Toward Romantic Relationships  
*(European Social Survey – Poland & Czech Republic)*

## 📌 Project Overview
This project explores the relationship between **religiosity** and **attitudes toward romantic relationships**, including cohabitation, having children outside of marriage, and the ideal age of marriage.  
The analysis is based on data from the **European Social Survey (ESS, Round 9)** and focuses on a comparison between **Poland and the Czech Republic**.

## 🎯 Research Goals
- Construct a **composite religiosity index** based on self-declared religiosity, prayer frequency, and church attendance  
- Examine how religiosity relates to:
  - approval of cohabitation  
  - approval of having children outside marriage  
  - ideal age of marriage  
- Compare patterns between Poland and the Czech Republic  
- Assess both **statistical significance** and **effect size** of observed relationships  

## 🛠 Tools & Technologies
- **R**
- **tidyverse**
- **ggplot2**
- **rio**
- **sjPlot**
- **rcompanion**
- **ESS survey data (.sav)**

## 🔍 Methods
- Data cleaning and handling missing values  
- Variable recoding and scale normalization  
- Construction of a **religiosity index**  
- Exploratory data analysis and visualization  
- Non-parametric statistical tests:
  - Kruskal–Wallis test
  - Chi-square test
- Effect size measures:
  - Epsilon squared
  - Cramér’s V  

## 📊 Key Findings
- Religiosity differs strongly between Poland and the Czech Republic
- Higher religiosity is associated with:
  - lower approval of cohabitation
  - lower approval of having children outside marriage
  - slightly higher ideal age of marriage
- Although many relationships are **statistically significant**, effect sizes are **small**, indicating limited substantive impact

## 📁 Files
- `Religiosity_and_Romantic_Attitudes.Rmd` – full analysis in R Markdown  
- `tabela_religijnosc_kohabitacja_PL.html` – cross table (Poland)  
- `tabela_religijnosc_kohabitacja_CZ.html` – cross table (Czech Republic)

## 🧠 Skills Demonstrated
- Data cleaning and preprocessing
- Index construction
- Statistical reasoning and interpretation
- Data visualization
- Working with survey data
- Clear analytical storytelling

## 📎 Data Source
European Social Survey (ESS), Round 9  
https://www.europeansocialsurvey.org
