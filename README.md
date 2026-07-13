# House-Price-Prediction-Project
A beginner-level machine learning project analyzing housing data using exploratory data analysis and linear regression. Includes data visualization (histogram, scatter plot, heatmap) and model evaluation using R² score.
The dataset includes basic housing attributes such as:
- Area  
- Number of stories  
- Price (target variable)

##  Project Workflow

### 1. Data Loading
The dataset is loaded into a Pandas DataFrame and inspected for structure and basic information.

### 2. Exploratory Data Analysis (EDA)
The following visualizations are used to understand the data:

- Histogram  
  - Distribution of house area  

- Scatter Plot  
  - Relationship between number of stories and price  

- Correlation Heatmap  
  - Shows relationships between all numerical features  

---

### 3. Model Building
A Linear Regression model is trained to predict housing prices based on the available features.

---

### 4. Model Evaluation
The model is evaluated using:

- R² Score  
  - Measures how well the model explains the variance in the target variable  

### 5. Prediction for a new house 

- A new house data is given to the model to predict the price for it.
- 
## Results
- The dataset shows relationships between features and housing price  
- Area and structural attributes have noticeable influence on price  
- Linear regression provides a simple baseline prediction model  

## Technologies Used
- Python  
- Pandas  
- NumPy  
- Matplotlib  
- Seaborn  
- Scikit-learn  

