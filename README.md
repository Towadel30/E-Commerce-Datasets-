# E-Commerce-Datasets-
This dataset contains online retail transactions including invoice numbers, Stock Code, Description, quantity, Invoice Date, unit price, customer id and country.
# E-commerce Dataset

## Dataset Understanding

## Data Cleaning

## Exploratory Data Analysis

## Visualizations

## Insights
import pandas as pd
import numpy as np
import matplotlib.pyplot as plt
import seaborn as sns
ecommerce = pd.read_csv(r"C:\Users\HP-PC\Desktop\internship\E-commerce.csv", encoding="latin1")
ecommerce.head()
InvoiceNo	StockCode	Description	Quantity	InvoiceDate	UnitPrice	CustomerID	Country
0	536365	85123A	WHITE HANGING HEART T-LIGHT HOLDER	6	12-01-10 08:26	2.55	17850.0	United Kingdom
1	536365	71053	WHITE METAL LANTERN	6	12-01-10 08:26	3.39	17850.0	United Kingdom
2	536365	84406B	CREAM CUPID HEARTS COAT HANGER	8	12-01-10 08:26	2.75	17850.0	United Kingdom
3	536365	84029G	KNITTED UNION FLAG HOT WATER BOTTLE	6	12-01-10 08:26	3.39	17850.0	United Kingdom
4	536365	84029E	RED WOOLLY HOTTIE WHITE HEART.	6	12-01-10 08:26	3.39	17850.0	United Kingdom

