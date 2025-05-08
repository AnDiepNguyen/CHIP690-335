# Project Title

Examining the distribution of serum PNC values between participants with and without key heart failure risk factors: coronary artery disease, heart attack, and high blood pressure.

## Installation
1. Create a virtual environment:
    - On Windows
     - Open Command Prompt or PowerShell.
     - Run the following command:
       ```
       python -m venv venv
       ```
2. Activate the virtual enviroment:
    - On Windows:
      - In Command Prompt or PowerShell, run:
        ```
        venv\Scripts\activate #on Windows
        ```
3. Install required packages.
    - Ensure the virtual environment is activated, then run the following command:
       ```
       pip install -r requirements.txt
       ```
### Usage
1. After completing installation. Open Jupyter Notebook, run:
       ```
       jupyter Notebook
       ```
2. Once jupyter opens in your browser, navigate to `milestone_2.ipynb` notebook and run the cells to explore the analysis.

#### Analysis
This analysis is a top level analysis on a set of a data that was previously used in study examining the serum PNC as a biomarker for heart failure within the general population. The study sampled two matched cohorts. Cohort A had no heart failure at serum collection or during follow-up. Cohort B developed heart failure after collection. A review of the demographics table indicates that Cohort A and Cohort B were comparable in key demographic characteristics including sex, age, and race. A summary of descriptive statistics for age, weight, height, heart rate, and blood pressure indicates that the two cohorts are very similar.

The analysis first look at the current standard biomarker for ruling in our ruling out heart failure, NTproBNP. Using >300 as the general cutoff for ruling in heart failure, along with excluding outliers, the boxplot did not show a clear difference in NTproBNP distribution between Cohort A and Cohort B.

A boxplot was then generated to compare PNC distribution between the two cohorts. Cohort A showed lower values across the median, interquartile range, and overall spread (excluding outliers), suggesting generally lower PNC levels among participants without heart failure at baseline or follow-up.

Three additional boxplots were created to compare the distribution of PNC values among participants with heart failure risk factors—coronary artery disease, heart attack, or high blood pressure—regardless of cohort assignment. In each comparison, participants without these risk factors consistently showed lower median values, narrower interquartile ranges, and shorter whiskers, indicating generally lower PNC levels than those with the risk factors.

This analysis provided a high-level overview of a dataset from a study that investigated PNC as a potential diagnostic marker for detecting subclinical heart failure in the general population. The findings are consistent with previous research, showing that PNC levels tend to be higher in participants with known heart failure risk factors such as coronary artery disease, heart attack, and high blood pressure.

   