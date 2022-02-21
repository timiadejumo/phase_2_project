# Analyzing King County Real Estate

-Student Names: Chris Helmerson, Tim Cleary, 'Timi Adejumo

## Overview

We have been contracted by a building company, Flatiron Construction Co., newly located in King County, WA. They want to enter the housing market and are unsure of which features of a new house are most important when looking to build and sell. We have been asked to source relevant data and provide the needed information.

---

### **Business Understanding**
At the onset, there are a lot of decisions a home builder must make. A home builder's dream is to make homes that tick all of the boxes on the buyer's checklist. However, the question a builder wants answered is exactly what the buyer wants in a home. Our client, Flatiron Construction Co. has given us the opportunity to answer that question as they foray into King County.  Currently, builders are facing major challenges, including escalation of prices of and a shortage of building materials, and labor shortages. On the other hand, the demand for homes has not slowed down. This means builders, like never before, must make the most use of the resources available.

---

### **Data Understanding and Analysis**
We sourced our data majorly off the King County Homes sales dataset, which is widely and openly available on the Internet. We were also able to source some additional data from the 
Capitol Impact Government Gateway website. The dataset is for house sales in King County, WA between the the years 2014 to 2015. The dataset is available in .csv
format. 
To analyse the data, we made use of the following Python libraries:
-Numpy v1.20.3, Pandas 1.1.3, Matplotlib 3.3.1, Statsmodel 0.12.0, Scipy 1.5.2, and Seaborn 0.11.0.

The following information pertaining to home sales is available readily on the datasets: 
date and price of sale of the home, location of the property (zipcode and longitudinal and latitudinal coordinates), size (in square ft) of each property, age, condition and number of bathrooms and bedrooms.



---

### **Data Preparation**
The King County Home sales dataset we worked with required cleaning in its raw state. It had 21 columns, and the 3 datatypes: integer, strings and floats. 
Some of the columns were also categorical in nature. 
**Datatype conversion**:    To better work with some of the columns, we had to cast them to other datatypes, for instance: 'sqft-basement' from string to float, 'date' column from string to datetime format, etc.
**Missing Values**:    We had to deal with null values in our dataset. Three columns had null values. Due to the relatively small number of null values we were able to apply modal imputation where needed to fill in the missing information. 
**Categorical data**:    Next we looked to get some of our data into numerical categories using OneHotEncoding and Ordinalencoding to work better (or at all) with our model. 
**Outliers**:    There was only a solitary case of outliers probably due to clerical errors. 
**Scaling**:    Before fitting the training data, we scaled the train and test data using the StandardScaler.

---

### **Modeling**

---

### **Regression Results**

---

### **Conclusion**


---

### **Repository Structure**
