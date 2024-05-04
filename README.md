# Boston_Housing_Price_Prediction

## Software and Tools Requirements

1. [Github Account] (https://github.com/)
2. [VS Code IDE] (https://code.visualstudio.com/)
3. [Heroku Account] (https://dashboard.heroku.com/)
4. [Git Cli] (https://git-scm.com/downloads)


## Create a Virtual Environment

```
conda create -p venv python==3.11.7 -y
```

```
Activate the virtual environment in the cmd prompt using: conda activate venv/
```

## Checking the model prediction using postman

Run the command in command prompt:

```
python app.py
```

# Attributes

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

## Building Docker Images

Dockers helps in setting base configurations which will eliminate all the issues like configuration issues, hardware issues, OS issues