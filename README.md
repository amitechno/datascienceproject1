# New York Rent Analysis

## Overview

This project analyzes a dataset of New York rental listings using the CRISP-DM framework. The primary goal is to uncover insights into rental prices, room types, and location trends in New York City.

### Key Questions Addressed:

1. **What factors influence the price of a listing?**
2. **Which neighborhoods or neighborhood groups have the highest number of listings?**
3. **Which room type (e.g., private room, shared room, entire home) is the most common?**

---

## Repository Structure

This project is contained in a single Jupyter Notebook for simplicity:


---

## Notebook Structure

The notebook follows the CRISP-DM framework:

### 1. **Data Loading and Preparation**
   - Loads the dataset (`dataset.csv`).
   - Cleans and preprocesses data, including handling missing values and converting categorical variables.

### 2. **Exploratory Analysis**
   - Examines relationships between features such as:
     - **Factors influencing listing prices**.
     - **Number of listings across different neighborhoods**.
     - **Distribution of room types**.

### 3. **Modeling**
   - Builds regression models to predict:
     - **Listing prices** based on room type, neighborhood, and other factors.
   
### 4. **Visualizations**
   - Creates visualizations to communicate insights:
     - Price distribution by neighborhood and room type.
     - Correlation between reviews and listing prices.
     - Number of listings per neighborhood group.

## Results and Insights

1. **Price Analysis**: 
   - The analysis shows that **room type**, **neighborhood group**, and **number of reviews** all have significant effects on the **listing price**. However, the linear regression model does not provide a strong fit to the data, and further improvements in feature selection, data preprocessing, or model choice may be necessary to achieve better predictive accuracy.

2. **Neighborhood Listings**: 
   - The neighborhood with the highest number of listings is **Manhattan**, followed by **Brooklyn**. This indicates that these neighborhoods are the most popular for both long-term and short-term rentals in New York City.

3. **Relation between Reviews and Price**: 
   - there is almost no linear correlation between the price of the listing and the number of reviews it has. In other words, higher-priced listings do not seem to have significantly more or fewer reviews compared to lower-priced listings.

For a detailed explanation of the results, please visit the following Medium article where the analysis and findings are discussed in depth:

[**Medium Article on New York Rent Analysis Results**](https://medium.com/@vit.amitsharma/blog-post-cracking-the-code-insights-from-the-2017-stack-overflow-developer-survey-0e27f41cd625)

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
jupyter notebook ny.ipynb



### Key Sections Added:
1. **License**: The project is under the MIT License, which is common for open-source projects.
2. **Author**: Amit Sharma - https://www.linkedin.com/in/amit-sharma-08011317/
3. **Acknowledgments**: 
   Dataset: The data used for this analysis was obtained from the publicly available Airbnb New York City dataset on Kaggle.
   Libraries: This project was built using Python libraries including pandas, matplotlib, seaborn, and scikit-learn.
   Special thanks to the authors of the original dataset for providing valuable insights into Airbnb listings

