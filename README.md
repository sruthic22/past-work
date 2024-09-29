# past-work
A collection of my completed projects showcasing my skills in data science.

## Lab Experiment Database and User Interface

This project is designed to streamline the management of lab experiments at Northeastern University. It involves creating a comprehensive database to track various laboratory components, including chemicals, reactants, labs, equipment, researchers, and experiments.

### Features:
- **Chemical Management**: Store and retrieve information about different chemicals, their properties, and reactivity.
- **Reactant Tracking**: Keep track of available reactants, their amounts, and expiration dates to ensure safe and effective usage.
- **Laboratory Information**: Manage details about different labs, including location and department affiliations.
- **Equipment Oversight**: Maintain records of lab equipment and their corresponding lab locations.
- **Researcher Data**: Track researchers associated with each lab and their roles in experiments.
- **Experiment Management**: Create and monitor experiments, linking them with the necessary chemicals and equipment.
- **Procedural Support**: Implement stored procedures to manage reactants and experiments efficiently.

### Tech Stack:
- **Database**: MySQL
- **Programming Language**: Java
- **Development Tools**: JDBC (Java Database Connectivity), SQL
- **Environment**: Local MySQL Server

This project enhances the organization and efficiency of lab operations, ensuring that all necessary components are easily accessible and properly documented.

## Zillow Housing Price Predictor

This project aims to analyze housing prices in the southern United States using data collected from Zillow.com. By employing machine learning algorithms and statistical modeling, we sought to create a predictive model for estimating home prices based on various characteristics of recently sold properties.

### Executive Summary:
The COVID-19 pandemic has significantly impacted the real estate market, particularly in the southern states, where home sales have surged. We scraped data from Zillow for recently sold houses in five southern states and applied four machine learning algorithms to develop a robust price prediction model. After performing feature selection and hyperparameter tuning, we found that Linear Regression provided the best performance, although limitations in the dataset prevented us from accurately determining the most influential features affecting house prices.

### Features:
- **Data Scraping**: Automated collection of housing data from Zillow, including details such as city, state, ZIP code, number of bedrooms and bathrooms, square footage, and selling price.
- **Machine Learning Models**: Utilization of various algorithms (k-nearest neighbors, Linear Regression, Lasso Regression, Ridge Regression) to predict housing prices.
- **Feature Selection**: Analysis of the most impactful features contributing to house price predictions.
- **Hyperparameter Tuning**: Optimization of model parameters to improve prediction accuracy.

### Tech Stack:
- **Programming Languages**: Python
- **Libraries/Frameworks**: Pandas, NumPy, Scikit-Learn, BeautifulSoup, Requests
- **Data Source**: Zillow.com
- **Development Environment**: Jupyter Notebook, Google Colab

### Data Acquisition:
The dataset consists of 1,062 samples collected from the top 20-25 most populated cities in Florida, Georgia, Alabama, South Carolina, and Tennessee. The features included in the dataset are year sold, ZIP code, number of bedrooms, number of bathrooms, square footage, month sold, broker, city, and state.

For more details on data scraping, check out our [data scraping code](https://github.com/jasmineliu0114/Zillow-Housing-Price-Predictor/blob/main/FP2_Dataset.ipynb) and the resulting dataset can be found [here](https://github.com/jasmineliu0114/Zillow-Housing-Price-Predictor/blob/main/real_estate_prices_in_the_south.csv).

