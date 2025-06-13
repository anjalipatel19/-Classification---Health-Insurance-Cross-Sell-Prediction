# Health Insurance Cross Sell Prediction

## Project Overview

This project applies machine learning classification techniques to predict whether existing health insurance customers will be interested in purchasing vehicle insurance. By analyzing demographic and policy-related data, the project helps insurance companies identify potential cross-sell opportunities and improve customer targeting strategies.

> **Project Type**: Classification 
> **Contributor**: *Anjali Patel*

## Project Summary

The dataset, sourced from **Almabetter**, consists of **381,109 rows and 12 columns**. The objective is to build a predictive model using customer and policy attributes to forecast the likelihood of a customer purchasing additional vehicle insurance (`Response` variable).

### Project Pipeline:

* **Data Preprocessing**: Merging, cleaning, and encoding data.
* **Exploratory Data Analysis (EDA)**: Univariate, Bivariate, and Multivariate analysis.
* **Feature Engineering**: Addressing outliers, missing values, and categorical encodings.
* **Model Training**: Logistic Regression, Decision Tree, and Random Forest.
* **Model Evaluation**: Compared models based on accuracy, with Random Forest performing best.

## Tools & Technologies Used

* **Language**: Python 3
* **Environment**: Jupyter Notebook
* **Libraries**:
  * `pandas`, `numpy` – data handling
  * `matplotlib`, `seaborn` – data visualization
  * `scikit-learn` – machine learning models and evaluation

## Key Insights

* **Vehicle Damage**: Customers with prior vehicle damage are more likely to opt for cross-sell offers.
* **Previously Insured**: Those who were not previously insured are more responsive to the offer.
* **Age Group**: Customers between 25–45 years showed higher interest in purchasing vehicle insurance.
* **Annual Premium**: Lower annual premium brackets show higher cross-sell conversion.
* **Region Code**: Some region codes have significantly higher positive responses.
* **Driving License**: Although most customers had a license, it wasn't a strong predictor alone.
* **Policy Sales Channel**: Certain channels perform significantly better in conversions.

## Visual Insights

Below are some visualizations from the analysis:

1. **Age vs Response Rate**
   ![1](https://github.com/user-attachments/assets/a9c9a925-4b02-42a7-b4ff-1c4a17947538)
   The response shows an upward trend between the ages of 20 to 35, remains relatively stable between the ages of 35 to 50, and then starts to decline for individuals aged 50 and above.

2. **Vehicle Damage vs Response**
   ![2](https://github.com/user-attachments/assets/945db401-caf1-4b13-97e3-9e9b6862b808)
   Highlights strong impact of previous damage history on purchase behavior.

3. **Customer Response by Policy Sales Channel**
   ![3](https://github.com/user-attachments/assets/54f9264f-8ae6-4cf3-a6f6-24d33ef39851)
   Customers between policy sales channel ranges of 40–45 and 120–125 are more responsive to cross-sell offers. This suggests certain agents or sales platforms are more effective.

4. **Impact of Previous Insurance Status on Response**
   ![4](https://github.com/user-attachments/assets/4202cd52-b1a4-4c24-8343-c7afdb26446b)
   Customers who were not previously insured are significantly more responsive to vehicle insurance offers, compared to those already covered.

5. **Correlation Heatmap**
   ![5](https://github.com/user-attachments/assets/c089d87b-e4aa-4e44-8bb4-188392f64bab)
   Displays the correlation between features, helping identify key drivers of customer response.

6. **Pair Plot of Key Numerical Features**
   ![6](https://github.com/user-attachments/assets/c76ca325-bea0-4fca-927c-a50835e56b41)
   Reveals interactions among Age, Premium, and Vintage with Response.

## Model Evaluation

| Algorithm           | Accuracy  |
| ------------------- | --------- |
| Logistic Regression | Moderate  |
| Decision Tree       | Good      |
| **Random Forest**   | **Best**  |

The **Random Forest classifier** achieved the highest accuracy and was chosen as the final model.

## Repository Structure

* **Classification - Health Insurance Cross Sell Prediction** – Main project folder
  * **Classification on Health Insurance Cross Sell Prediction.ipynb** – Jupyter Notebook containing the full analysis
  * **TRAIN-HEALTH INSURANCE CROSS SELL PREDICTION.csv** – Dataset used for analysis
* **LICENSE** – MIT License file
* **README.md** – Documentation explaining the project

##  License

This project is licensed under the **MIT License**. See the `LICENSE` file for more information.
