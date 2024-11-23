# Stack Overflow Developer Survey 2017 Analysis

## Overview

This project analyzes the 2017 Stack Overflow Developer Survey dataset using the CRISP-DM framework. The primary goal is to uncover insights into developer salaries, technology preferences, and job satisfaction trends.

### Key Questions Addressed:

1. **How do developer salaries differ across countries, and what factors contribute to these differences?**
2. **Which programming languages or technologies correlate with higher salaries?**
3. **How does remote work frequency affect job satisfaction and productivity?**

---

## Repository Structure

This project is contained in a single Jupyter Notebook for simplicity:


---

## Notebook Structure

The notebook follows the CRISP-DM framework:

### 1. **Data Loading and Preparation**
   - Loads the dataset (`survey_results_public.csv`).
   - Cleans and preprocesses data, including handling missing values and creating derived variables (e.g., `YearsCodingTransformed`).

### 2. **Exploratory Analysis**
   - Examines relationships between features such as:
     - **Geographic salary distribution**.
     - **Technology correlation with salary**.
     - **Remote work and job satisfaction**.

### 3. **Modeling**
   - Builds linear regression models to predict:
     - Developer **salaries** based on experience, country, and other features.
     - Developer **job satisfaction** based on remote work frequency and other variables.

### 4. **Visualizations**
   - Creates visualizations to communicate insights:
     - Salary distribution by country.
     - Technology correlation with salary.
     - Trends in remote work satisfaction.

---

## How to Run the Notebook

### 1. **Clone the Repository**

```bash
git https://github.com/DrRashmi-Stat/datascience-project1.git
cd datascience-project1

2. Install Dependencies
Ensure you have Python 3.7+ installed. Install the required packages using:

pip install -r requirements.txt

3. Run the Notebook
Launch Jupyter Notebook or Jupyter Lab:
jupyter notebook StackOverflow_2017_Analysis.ipynb



