# Data-Analyst-Internship-Task-15

# Customer Segmentation using RFM Analysis

## About this project
In this task, I performed Customer Segmentation using RFM (Recency, Frequency, Monetary) Analysis on an E-Commerce dataset.

The main goal of this project is to understand customer buying behaviour and group customers based on how recently they purchased, how often they purchase, and how much money they spend.

This helps businesses target the right customers with the right marketing strategies.

---

## Tools Used
- Python
- Google Colab
- Pandas
- NumPy
- Matplotlib

---

## Steps I followed

1. Loaded the dataset in Google Colab  
2. Cleaned the data by removing null CustomerIDs and cancelled orders  
3. Converted InvoiceDate into datetime format  
4. Created TotalAmount column (Quantity × UnitPrice)  
5. Calculated:
   - Recency
   - Frequency
   - Monetary
6. Assigned scores using quantiles  
7. Segmented customers into different groups  
8. Visualized the segments using a bar chart  
9. Exported the final results to CSV and text files  

---

## Customer Segments Created
- Champions
- Loyal Customers
- Potential Loyalists
- At Risk
- Hibernating

---

## Business Actions
- Champions → give rewards and special offers
- Loyal → upsell and cross-sell products
- Potential → send reminders and discounts
- At Risk → win-back campaigns
- Hibernating → re-engagement emails

---

## Conclusion
This project helped me understand how customer data can be used to segment users and support business decisions.  
I learned data cleaning, RFM calculation, segmentation, and basic visualization using Python.

