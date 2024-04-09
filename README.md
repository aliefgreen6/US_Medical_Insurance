# US_Medical_Insurance
This repository contains Python code for analysing U.S. medical insurance costs dataset. 

The repository contains the following files:

<ul>
  <li><b>insurance.csv:</b> This is the dataset file containing information about U.S. medical insurance costs. It includes columns such as age, sex, BMI (Body Mass Index), number of children, smoker status, region, and charges.</li>
  <li><b>analysis.ipynb:</b> This Notebook performs the analysis on the insurance dataset. It includes code for loading the data, computing descriptive statistics, creating visualizations, conducting inferential statistics (such as t-tests and ANOVA), and performing regression analysis to predict medical charges.</li>
</ul>


**Analysis.py Overview:**

<ul>
  <li><b>Data Loading and Descriptive Statistics:</b>
    <ul>
      <li>The code loads the insurance dataset using Pandas and computes basic descriptive statistics such as mean, median, quartiles, standard deviation, and mode for the numerical variables.</li>
      <li>Descriptive statistics are displayed in a user-friendly format.</li>
    </ul>
  </li>
  <li><b>Visualizations:</b>
    <ul>
      <li>Histograms and box plots are created to visualize the distribution of medical charges and compare charges across different categories (e.g., smoker status, region).</li>
    </ul>
  </li>
  <li><b>Inferential Statistics:</b>
    <ul>
      <li>Functionality is implemented to calculate confidence intervals for sample means.</li>
      <li>T-tests and ANOVA are performed for group comparisons:
        <ul>
          <li>T-test compares charges between smokers and non-smokers.</li>
          <li>ANOVA compares charges across different regions.</li>
        </ul>
      </li>
    </ul>
  </li>
  <li><b>Regression Analysis:</b>
    <ul>
      <li>Linear regression is conducted to predict medical charges based on predictors such as age, BMI, children, and smoker status.</li>
      <li>The regression model's summary, actual vs. predicted charges scatter plot, and residuals vs. predicted charges plot are provided.</li>
    </ul>
  </li>
  <li><b>Explanation:</b>
    <ul>
      <li>A brief explanation is included, highlighting the purpose and importance of each analysis conducted in the code.</li>
    </ul>
  </li>
</ul>

**Running the Code:**

Ensure that Python and required libraries (Pandas, NumPy, SciPy, Statsmodels, Seaborn, Matplotlib) are installed.
Download the insurance dataset ('insurance.csv') and place it in the same directory as the Python script.
Execute the script to perform the analysis.
Note:This code provides insights into medical insurance costs based on various factors but does not imply causation. Additional analysis may be required for deeper insights.
Feel free to customize the code or incorporate additional analyses as needed.
