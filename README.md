# Singapore-Resale-Flat-Prices-Predicting

Introduction: The objective of this project is to develop a machine learning model and deploy it as a user-friendly online application to deliver precise predictions regarding the resale values of apartments in Singapore. This predictive model will derive insights from historical transactions involving resale flats, with the aim of assisting both prospective buyers and sellers in assessing the value of a flat upon resale. Numerous factors influence resale prices, such as location, apartment type, total square footage, and lease duration. Providing customers with an estimated resale price based on these factors is a key aspect through which a predictive model can help navigate the challenges associated with property transactions.

Requirements
Python
pandas
numpy 
streamlit 
scikit-learn

Project Workflow Overview:

The project unfolds through the following fundamental steps:

Dataset Compilation:
The Resale Flat Prices dataset comprises five distinct CSV files, each corresponding to a specific time period: 1990 to 1999, 2000 to 2012, 2012 to 2014, 2015 to 2016, and 2017 onwards. Consequently, a pivotal task involves consolidating these separate CSV files into a cohesive dataset.

Data Transformation and Pre-processing:
The data undergoes conversion into a format conducive to analysis, incorporating necessary cleaning and pre-processing procedures. Essential features such as town, flat type, storey range, floor area, flat model, and lease commence date are extracted. Additionally, any supplementary features with the potential to enhance prediction accuracy are created.

Model Construction:
The primary goal is to formulate a machine learning regression model employing the decision tree regressor. This model is specifically designed to accurately predict the continuous variable 'resale_price'.

Web Application Development:
A pivotal aspect of the project involves the creation of a Streamlit webpage. This webpage facilitates user interaction by allowing input of values for each column. The ultimate output is the anticipated 'resale_price' value for flats in Singapore based on the provided inputs.





