# Hypothesis Testing of International Soccer Matches

## Project Overview
This project employs statistical hypothesis testing to evaluate whether women's international soccer matches have significantly more goals scored compared to men's matches, using historical FIFA World Cup data since 2002. Findings from this analysis can support insightful sports journalism and reporting.

## Objectives
- Determine if more goals are scored in women's international soccer matches compared to men's.
- Perform hypothesis testing at a 10% significance level.

## Hypotheses
- **Null Hypothesis (H0):** The mean number of goals scored in women's matches is equal to men's matches.
- **Alternative Hypothesis (H1):** The mean number of goals scored in women's matches is greater than men's.

## Tools & Techniques
- **Python Programming:** Data analysis and statistical testing.
- **Pandas & Matplotlib:** Data preparation and visualization.
- **Pingouin & SciPy:** Statistical hypothesis testing (Wilcoxon-Mann-Whitney test).

## Analysis Steps
1. **Data Preparation:**
   - Loaded datasets `women_results.csv` and `men_results.csv`.
   - Converted "date" columns to datetime format.
   - Filtered for FIFA World Cup matches since January 1, 2002.

2. **Exploratory Analysis:**
   - Assessed data normality using visualizations.
   - Established non-normal distribution of goals scored.

3. **Hypothesis Testing:**
   - Conducted a Wilcoxon-Mann-Whitney test.
   - Extracted p-value and interpreted test outcomes.

## Results
- **P-Value:** Calculated and interpreted at a 10% significance level.
- **Decision:** Determined whether to reject or fail to reject the null hypothesis based on statistical outcomes.


## Conclusions
The hypothesis testing provided a statistical basis for understanding differences in scoring between men's and women's international soccer, contributing valuable insights for sports analysis and journalism.