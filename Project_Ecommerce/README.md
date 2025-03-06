# Project: Ecommerce Olist

## Description

This was the final project of business Intelligence diploma. I loaded and transformed the data with pentaho workbench and the final tables were allocate in PostgreSQL. Consequently the dashboard was made in PowerBI

Dataset: 
https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce

Brazilian ecommerce that by 2019 had generated $27MM in sales.


Objectives:

-Analysis of current sales (day, weeks, month, year).
-Analyze categories that satisfy customers the most.
-Obtain detailed information on current sales and how the market is projecting the best-selling products.
-Analyze current sales by city and most common payment method.



Picture 1 shows the trransactional model from kagle.com
![image](https://github.com/user-attachments/assets/fd36cb73-80f2-4343-ad96-ddbb4c7e96b6)

How do we go from transactional model to dimensional model?
I used Pentaho workbench to identify nulls values, duplicated values, create dim and fact tables and made an automatic ETL process.



![image](https://github.com/user-attachments/assets/588c70a4-f5ad-440e-8e21-41a5b24408a5)


In (picture 2) shows you the ETL process.



Then, I connect this tables with PowerBI, to make a dashborad as a part of solution for a unreal business problem.
This dataset is a part from Brazilian ecommerce. there is nine tables : 
customer
geolocation
seller 
payments
products
category name (english and portuguese)
order (orders items, orders, orders payment)

The final goal was visualize sale performace by  amount, time, category and other features related to this.

![alt text](image.png)
Picture 3 PowerBI dashboard
