<!-- ### House_prediction -->
### Boston House Pricing Prediction

### Software And Tools Requirements

1. [Github Account](https://github.com)
2. [Heroku Account](https://heroku.com)
3. [VS Code IDE](https://code.visualstudio.com/)
4. [Git CLI](https://git-scm.com/book/en/v2/Getting-Started-The-Command-Line)

---
create a new environment
```
    python3 -m venv venv
    source venv/bin/activate

```

### Project Description

This project is based on predicting house prices using **Linear Regression** on the Boston Housing dataset.  
The model is trained using Python and machine learning libraries and saved for further use.

---

### How to Run the Project

1. Clone the repository
2. Open the project in VS Code
3. Create and activate the virtual environment
4. Install dependenies
```
    pip install -r requirements.txt

```
5.	Run the Flask application:
```
    python app.py

```
6.	Open your browser and visit
---


### API endpoint

POST /predict_api

Sample JSON Input
```
    {
  "data": {
    "crim": 0.00632,
    "zn": 18.0,
    "indus": 2.31,
    "chas": 0,
    "nox": 0.538,
    "rm": 6.575,
    "age": 65.2,
    "dis": 4.09,
    "rad": 1,
    "tax": 296,
    "ptratio": 15.3,
    "b": 396.9,
    "lstat": 4.98
  }
}

```


### Project  Structure

- app.py – Flask application
- Boston.ipynb – Model training and analysis
- regModel.pkl – Trained model
- scaling.pkl – Feature scaler
- templates/home.html – Frontend UI
- requirements.txt – Project dependencies




### Tech Stack
- Python
- Flask
- NumPy
- Pandas
- Scikit-learn
- Matplotlib
- Gunicorn

---

### Deployment
- deployed on Render
- Flask app served using Gunicorn

### Model Used
- Linear Regression

 