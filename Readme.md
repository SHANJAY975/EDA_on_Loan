# Loan Dataset Exploratory Data Analysis (EDA)

## Overview

This repository contains the exploratory data analysis (EDA) of a loan dataset. The primary goal of this analysis is to uncover patterns, detect anomalies, and gain insights into the factors influencing loan approval.

## Dataset

The loan dataset includes various features related to loan applicants, such as demographic details, loan characteristics, and credit history. Key features include:

- Applicant Income
- Coapplicant Income
- Loan Amount
- Loan Amount Term
- Credit History
- Gender
- Marital Status
- Education
- Self Employed
- Property Area
- Loan Status (Target variable)

## Analysis

The EDA process involved the following steps:

1. **Data Cleaning**: Handling missing values, correcting data types, and addressing inconsistencies.
2. **Univariate Analysis**: Analyzing individual features to understand their distribution and key statistics.
3. **Bivariate Analysis**: Exploring relationships between pairs of variables, particularly the target variable (Loan Status).
4. **Multivariate Analysis**: Investigating interactions among multiple variables to identify more complex patterns.
5. **Visualization**: Creating plots and charts to visually represent the data and the findings from the analysis.

## Key Findings

- **Income and Loan Amount**: Higher applicant income and lower loan amounts tend to have higher approval rates.
- **Credit History**: A good credit history is a strong indicator of loan approval.
- **Gender and Marital Status**: Male applicants and married applicants have higher approval rates.
- **Education and Employment**: Graduates and self-employed individuals show distinct patterns in loan approval.

## Visualizations

The repository includes various visualizations to illustrate the findings, such as:

- Histograms
- Box plots
- Bar charts
- Heatmaps
- Pair plots

## Usage

To explore the analysis, follow these steps:

1. Clone the repository:
    ```bash
    git clone https://github.com/SHANJAY975/EDA_on_Loan
    ```
2. Navigate to the project directory:
    ```bash
    cd EDA_on_Loan
    ```
3. Open the Jupyter Notebook to view the EDA:
    ```bash
    jupyter notebook EDA_on_Loan.ipynb
    ```

## Conclusion

This EDA provides valuable insights into the factors affecting loan approval, which can be useful for improving loan approval processes and developing predictive models.

## Contributing

Feel free to fork this repository, submit issues, and send pull requests. Contributions are welcome!

## License

This project is licensed under the [MIT License](LICENSE).
