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

