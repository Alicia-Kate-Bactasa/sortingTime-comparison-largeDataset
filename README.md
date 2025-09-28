# Customer Survey Data Analysis

**Note:** I'm using this notebook to experiment around with the data in `jupyter notebook`. Here, I clean the data, try out different sorting algorithms (Merge Sort, Bubble Sort, Selection Sort), and compare how fast they are. Just for learning and testing things out!

## Project Overview
This side project analyzes a **customer satisfaction survey dataset** from a food delivery service. The dataset contains ratings and feedback from customers regarding **Delivery, Food, Speed**, and **Order Accuracy**. The goal is to clean, organize, and sort the data while comparing the efficiency of different sorting algorithms.


## Dataset Source and Credit
**Dataset:** Customer Satisfaction Survey at Kashmir Cafe  
**Creator:** Ahmed Ali Khan  
_dataset extracted from kaggle.com_

This dataset collects responses from customers regarding their experience with Kashmir Cafe's services. It provides insights into customer satisfaction levels, delivery performance, food quality, speed, and order accuracy.

**Columns:**
- `Customer` 
- `Delivery` – Overall delivery experience rating (1–5)  
- `Food` – Food quality rating (1–5)  
- `Speed` – Delivery speed rating (1–5)  
- `Accuracy` – Whether the order was accurate (Yes/No)  

**License:** CC0 1.0 Universal Public Domain Dedication  


## Features of This Project
1. **Data Cleaning:**  
   - Renamed columns for readability  
   - Calculated total counts of each rating (1–5) across all satisfaction metrics  

2. **Sorting Algorithms Implemented:**  
   - **Merge Sort** – Efficient for large datasets  
   - **Bubble Sort** – Simple but slower for large datasets  
   - **Selection Sort** – Moderate efficiency for smaller datasets  

3. **Performance Analysis:**  
   - Calculated the time taken by each sorting algorithm  
   - Compared efficiency to recommend the best method for large datasets  

4. **Final Dataset:**  
   - Sorted customer records by Delivery rating  
   - Summary row shows total counts of each rating and sorting times  
   - Columns renamed and text-wrapped for readability in google sheets  

## How to Use
1. Open the Jupyter Notebook to view analysis and sorting code.  
2. The processed dataset is saved as `customer_survey_sorted_final.csv`.  
3. Open in Google Sheets or Excel to explore:  
   - Summary of ratings  
   - Sorted customer data  
   - Timing comparisons for Merge, Bubble, and Selection sorts  

# Insight Preview:

<img width="272" height="74" alt="Screenshot 2025-09-28 at 4 12 09 PM" src="https://github.com/user-attachments/assets/14112aae-ca77-4254-a6c1-6ac9b0d6f07b" />


**Note:** This dataset is intended for research and analysis purposes. Please observe data privacy and ethical considerations when working with customer feedback data.
