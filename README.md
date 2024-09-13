# The Tragic Discovery of Handwashing: t-Tests & Distributions

![Dr Semmelweis](https://i.imgur.com/gugIA5r.png)

## Introduction

This project explores the historical data from Dr. Ignaz Semmelweis' research, conducted in the 1840s, to analyze the impact of handwashing on reducing maternal deaths from childbed fever (puerperal fever). The analysis includes statistical tests, visualizations, and distributions to highlight the dramatic effect of handwashing on maternal mortality rates.

Dr. Semmelweis' findings changed the course of medical history by establishing the importance of hygiene in medical settings. This notebook steps into his shoes to uncover the insights from the data he collected between 1841 and 1849.

## Data Sources

- **Annual Data:** Births and deaths by clinic from 1841 to 1849.
- **Monthly Data:** Detailed data of births and deaths per month over the same time period.

**Original Research:**
- [German Version of Dr. Semmelweis’ Research](http://www.deutschestextarchiv.de/book/show/semmelweis_kindbettfieber_1861)
- [English Translation](http://graphics8.nytimes.com/images/blogs/freakonomics/pdf/the%20etiology,%20concept%20and%20prophylaxis%20of%20childbed%20fever.pdf)

## Technologies Used

- **Python**: Data analysis and visualization.
- **Pandas**: Data manipulation and cleaning.
- **Seaborn & Matplotlib**: Data visualization (KDE plots, line charts, box plots).
- **Plotly**: Interactive visualizations.
- **SciPy**: Statistical tests (t-tests).

## Key Findings

- **Death Rate Before and After Handwashing**: A significant drop in the percentage of deaths after handwashing was made mandatory in 1847.
- **t-Test Results**: Statistical tests show that the difference in death rates before and after handwashing is highly significant (p-value < 0.01).
- **Visualizations**: Clear visual representation of death rates before and after handwashing, using KDE plots and twin axis line charts.

## Project Overview

### 1. Data Exploration

- Investigated the data using `pandas` to check for missing values, duplicates, and descriptive statistics.
- Calculated the percentage of deaths before and after handwashing.

### 2. Visualizations

- **Births and Deaths Over Time**: Created twin axis charts to visualize the monthly birth and death trends.
- **Clinic-Specific Analysis**: Compared Clinic 1 and Clinic 2 death rates.
- **Moving Average**: Calculated and plotted a 6-month rolling average of the death rate before handwashing.

### 3. Statistical Analysis

- **t-Test**: Conducted a two-sample t-test to show that the reduction in death rates post-handwashing was statistically significant.
- **Kernel Density Estimate (KDE)**: Used KDE plots to visualize the distribution of death rates before and after handwashing.

### 4. Key Visualizations

![Visual](https://i.imgur.com/F9DOJxx.png)

- **Total Monthly Births and Deaths**
- **Proportion of Deaths by Clinic**
- **Rolling Average of Death Rates**
- **KDE Plots of Death Rates Before and After Handwashing**

## Conclusion

Dr. Semmelweis' discovery of handwashing dramatically reduced maternal deaths from puerperal fever. Our analysis shows that handwashing reduced the chance of death during childbirth by approximately 7.59%. This reduction is both visually apparent and statistically significant based on the t-test results.

## How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/Prathamesh326/The-Tragic-Discovery-of-Handwashing-t-Tests-Distributions.git
   ```
   
2. Run the Jupyter notebook:
   ```bash
   jupyter notebook Dr_Semmelweis_Handwashing_Discovery_(start).ipynb
   ```

## License

This project is licensed under the MIT License.
