# Analysis-of-factors-affecting-Airbnb-pricing
End-to-end data analysis and modelling of AirBnB listings, covering data cleaning, exploratory analysis, regression, NLP-based sentiment analysis, and decision tree classification — implemented in Python using Jupyter Notebook.

Authors  
	•	Karthik Ramanathan  
	•	Sivakumar Nishaanth 

Course: MA0218 / Introduction to Data Science and Artificial Intelligence  
Instructor: Dr Imen Dhief

**Project Objectives**

This project aims to:  
	•	Clean and preprocess a real-world AirBnB dataset  
	•	Perform exploratory data analysis (EDA) to identify pricing and location trends  
	•	Build regression models to explain listing prices  
	•	Apply NLP sentiment analysis on textual reviews  
	•	Use decision tree classification to evaluate predictive performance  

**Methodology & Structure**

1️⃣ Data Cleaning & EDA  
	•	Data type conversions and missing-value handling  
	•	Descriptive statistics and visualisations  
	•	Interactive geospatial analysis using Folium  

2️⃣ Regression Analysis  
	•	Univariate linear regression  
	•	Multivariate linear regression  
	•	Model evaluation using Mean Squared Error (MSE)  

3️⃣ NLP & Sentiment Analysis  
	•	Text preprocessing (tokenisation, stopword removal, lemmatisation)  
	•	VADER sentiment scoring  
	•	Regression analysis incorporating sentiment features  

4️⃣ Classification (Decision Trees)  
	•	Feature engineering  
	•	Decision tree model training  
	•	Evaluation using confusion matrix and recall  

**Dataset**

• listings.csv — Structured dataset of AirBnB property attributes, pricing, and geographic information    
• reviews.csv — Unstructured text dataset of guest reviews used for NLP and sentiment analysis  
• calendar.csv — Time-series dataset capturing daily availability and price fluctuations for listings  

**Tech Stack**

Languages & Tools  
	•	Python (Jupyter Notebook)  

Libraries  
	•	Data Analysis: pandas, numpy  
	•	Visualisation: matplotlib, seaborn, folium  
	•	Machine Learning: scikit-learn  
	•	NLP: nltk (VADER)  
	•	Model Visualisation: graphviz  
