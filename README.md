
# Global Income Inequality Analysis

## Project Overview

This project analyzes global income inequality using the WIID dataset to understand distribution patterns, regional differences, and relationships with economic indicators such as GDP per capita and population.

The goal is to uncover meaningful insights about how inequality varies across countries, regions, and income groups over time.

##  Dataset Description

* Dataset: World Income Inequality Database (WIID)
* Key Metric: **Gini Coefficient** (measure of income inequality)
* Data includes:

  * Countries and regions
  * Income groups (low, middle, high)
  * GDP per capita
  * Population
  * Time-based inequality trends

##  Objectives

* Analyze global distribution of income inequality
* Compare inequality across regions
* Study relationship between GDP per capita and inequality
* Examine inequality differences across income groups
* Identify countries with extreme inequality levels
* Analyze historical trends in inequality

##  Key Analysis Performed

###  Distribution Analysis

* Most countries fall in **30–50 Gini range**
* Peak concentration around **30–40**
* Extreme inequality values are rare
* Slight positive skew (few countries with very high inequality)

###  Regional Analysis

* **Africa** → Highest inequality & largest variation
* **Americas** → Consistently high inequality
* **Asia** → Mixed inequality levels
* **Europe** → Lowest and most stable inequality
* **Oceania** → Moderate inequality with some variation

###  GDP vs Inequality

* Overall **negative trend** → higher GDP → lower inequality
* High variation in low-income countries
* High-income countries show more stability
* Exceptions exist (e.g., high GDP but high inequality)

###  Income Group Comparison

* Low income → highest inequality (~45+)
* Middle income → moderate inequality
* High income → lowest inequality (~30–35)
* Trend: **Inequality decreases as income increases**

###  Country-Level Insights

* High inequality countries:

  * South Africa, Namibia, Lesotho
* Low inequality countries:

  * Slovakia, Andorra, Czech regions

###  Trend Over Time

* Decrease (1870–1900)
* Increase (early 1900s)
* Fluctuations during economic crises
* Stability post-1950
* Slight increase after globalization (post-1990)

###  Population vs Inequality

* No strong correlation
* Small countries → high variation
* Large countries → more stable inequality

##  Tools & Technologies

* Python
* Pandas
* Matplotlib / Seaborn
* Jupyter Notebook

##  Project Structure

* `WIID.ipynb` → Data analysis notebook
* `Global Income Inequality Analysis.pdf` → Report
* `README.md` → Project documentation

##  Key Insights

* Inequality is **moderate globally but varies widely by region**
* Wealthier countries tend to be more equal—but not always
* Government policies and economic systems play a major role
* Inequality trends are influenced by **historical events and globalization**

##  Conclusion

This analysis highlights that income inequality is a complex issue influenced by multiple factors beyond just economic growth. While higher income levels generally reduce inequality, regional patterns, policies, and historical contexts significantly impact income distribution.
