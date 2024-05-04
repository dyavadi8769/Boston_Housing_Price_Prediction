# Boston_Housing_Price_Prediction


## Project Overview

This is a comprehensive machine learning project focused on predicting housing prices in Boston. It encapsulates the entire workflow of a machine learning project right from data acquisition and preprocessing, through model training with Linear Regression, to deployment. The project highlights techniques like exploratory data analysis, feature standardization, and model serialization. Deployed via Docker containers and Heroku, this project is a practical demonstration of using machine learning to address real-world issues in real estate pricing.


## Steps Involved

1. Data Handling: Acquisition and preprocessing of the Boston housing dataset.
2. Exploratory Data Analysis: Statistical analysis and visualization to understand underlying patterns.
3. Feature Engineering: Standardization and normalization to improve model performance.
4. Model Training: Implementation of Linear Regression and performance evaluation using metrics like RMSE.
5. Deployment: Deployment of the trained model using Docker and Heroku for real time predictions.
6. CI/CD Pipeline: Automated updates and deployment through GitHub Actions.


## Attributes

1. CRIM - Crime Rate Per Capita
2. ZN - Proportion of Residential Land Zoned
3. INDUS - Proportion of Non-Retail Business Acres
4. CHAS - Charles River Adjacency (Dummy Variable)
5. NOX - Nitric Oxides Concentration (ppm)
6. RM - Average Rooms Per Dwelling
7. AGE - Proportion of Pre-1940 Built Homes
8. DIS - Weighted Distance to Employment Centers
9. RAD - Accessibility to Radial Highways Index
10. TAX - Property Tax Rate Per $10,000
11. PTRATIO - Pupil-Teacher Ratio by Town
12. B - Proportion of Black Residents (Transformed)
13. LSTAT - Percentage of Lower Status Population


## Software and Tools Requirements

1. [Github Account] (https://github.com/)
2. [VS Code IDE] (https://code.visualstudio.com/)
3. [Heroku Account] (https://dashboard.heroku.com/)
4. [Git Cli] (https://git-scm.com/downloads)


## Create a Virtual Environment in VS Code

```
conda create -p venv python==3.11.7 -y
```

Activate the virtual environment in the cmd prompt using
```
conda activate venv/
```


## Building Docker Images

Dockers helps in setting base configurations which will eliminate all the issues like configuration issues, hardware issues, OS issues


## Checking the model prediction using Postman

Run the command in command prompt:

```
python app.py
```
Check the model prediction by sending the below json text using postman REST API at http://127.0.0.1:5000:


```
{
    "data": {
        "CRIM": 0.00632,
        "ZN": 18.2,
        "INDUS": 2.31,
        "CHAS": 0,
        "NOX": 0.538,
        "RM": 6.575,
        "AGE": 25.0,
        "DIS": 4.09,
        "RAD": 1,
        "TAX": 296,
        "PTRATIO": 15.3,
        "B": 396.6,
        "LSTAT": 4.98
    }
}

```


## Contributing

Contributions to this project are Welcome. Please fork the repository and submit a pull request.