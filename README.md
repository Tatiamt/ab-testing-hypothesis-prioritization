\# A/B Testing and Hypothesis Prioritization for an E-commerce Platform



\## Business Problem



The marketing team of an e-commerce company proposed several hypotheses to increase revenue.  

The goal of this project was to prioritize these hypotheses and evaluate the impact of a product change through an A/B test.



\---



\## Dataset



The analysis is based on three datasets:



\- \*\*hypotheses\_us.csv\*\* — hypotheses with Reach, Impact, Confidence, and Effort

\- \*\*orders\_us.csv\*\* — transaction data including revenue and user group

\- \*\*visits\_us.csv\*\* — daily number of visits per test group



\---



\## Methodology



The project was conducted in the following steps:



1\. Hypothesis prioritization using \*\*ICE and RICE frameworks\*\*

2\. Data preprocessing and validation

3\. Detection and removal of outliers:

&#x20;  - Users with more than 2 orders

&#x20;  - Orders with value above the 99th percentile (830.3)

4\. Exploratory data analysis:

&#x20;  - Cumulative revenue

&#x20;  - Conversion rate

&#x20;  - Average order value

5\. Statistical testing using the \*\*Mann–Whitney U test\*\*



\---



\## Key Findings



\- Group B achieved a \*\*\~19% increase in conversion rate\*\* (statistically significant)

\- No statistically significant difference in \*\*average order value\*\*

\- Higher revenue in Group B is driven by increased conversion

\- Results remained consistent after removing outliers



\---



\## Business Recommendation



The experiment should be \*\*stopped\*\*, and \*\*version B should be implemented\*\*.



The tested change increases the probability of purchase without affecting the average order value, resulting in higher total revenue.



\---



\## Tools



\- Python

\- Pandas

\- NumPy

\- Matplotlib

\- SciPy

