# NYC Taxi Fare Analysis – Statistical Review and A/B Testing

## Project Overview

The New York City Taxi & Limousine Commission (NYC TLC) partnered with Automatidata to explore ways to increase taxi driver revenue. 

This phase of the project focuses on **statistical analysis and A/B testing** to examine whether a customer’s **payment method (credit card or cash)** influences the **total fare amount** of a taxi ride.

By analyzing taxi trip data and applying statistical hypothesis testing, the project aims to determine whether encouraging credit card payments could lead to higher overall revenue for taxi drivers.

---

## Business Problem

Taxi drivers receive varying amounts of tips and total fares depending on several factors. One potential factor is the **payment method used by customers**.

The main question addressed in this analysis is:

**Do customers who pay with credit cards tend to generate higher total fares compared to customers who pay with cash?**

Understanding this relationship can help the NYC TLC develop strategies to increase revenue for taxi drivers.

---

## Project Objective

The objective of this project is to:

- Analyze the relationship between **payment type and total fare amount**
- Perform statistical analysis to compare fare distributions
- Conduct an **A/B test** to determine whether payment method significantly affects taxi fare totals
- Provide actionable insights to improve revenue generation

---

## A/B Testing Methodology

To evaluate the impact of payment method on total fare amount, the Automatidata team conducted an **A/B test experiment**.

### Experiment Design

Customers were randomly divided into two groups:

**Group A (Treatment Group)**
- Customers required to pay using **credit cards**

**Group B (Control Group)**
- Customers required to pay using **cash**

Random assignment allows the experiment to isolate the effect of payment type and draw **causal conclusions** about how payment methods influence total fares.

---

## Analysis Process

The following steps were conducted during the statistical analysis:

### 1. Data Collection
Sample taxi trip data was collected where customers were randomly assigned to payment groups.

### 2. Descriptive Statistics
Descriptive statistics were computed to understand:

- Average total fare amount
- Distribution of fares
- Differences between payment groups

### 3. Hypothesis Testing

A **two-sample t-test** was performed to determine whether there is a **statistically significant difference** between the average total fares of the two groups.

---

## A/B Test Results

The statistical test revealed that:

- There is a **statistically significant difference** between the average total fare amounts of customers paying with credit cards and those paying with cash.
- Customers who paid using **credit cards showed higher total fare amounts** compared to those who paid with cash.

These findings suggest that payment method can influence the overall revenue generated from taxi rides.

---

## Key Business Insight

Encouraging customers to pay with **credit cards** may increase overall revenue for taxi drivers.

Customers who use credit cards tend to produce **higher total fares**, which may also include higher tipping behavior.

---

## Recommendations

Based on the results of the A/B test, the Automatidata data team recommends that the NYC TLC encourage credit card payments through strategies such as:

- Installing signage inside taxis indicating that **credit card payments are preferred**
- Encouraging drivers to verbally inform passengers that **credit card payments are recommended**
- Promoting digital and card-based payment options across the taxi network

These strategies may help increase driver earnings and improve overall service efficiency.

---

## Tools and Technologies

- Python
- Pandas
- NumPy
- SciPy
- Matplotlib
- Seaborn
- Jupyter Notebook

---

## Statistical Techniques Used

- Descriptive Statistics
- Hypothesis Testing
- Two-Sample t-Test
- A/B Testing Methodology
- Data Visualization

---

## Expected Impact

Implementing the insights from this analysis could:

- Increase taxi driver revenue
- Encourage digital payment adoption
- Improve operational efficiency within NYC taxi services

---

## Author

This project was developed as part of a **data analytics study focused on statistical analysis and experimental design using NYC Taxi & Limousine Commission data.**
