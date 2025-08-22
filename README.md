## Heart-Disease-Prediction

This Project is mainly divided into two parts:

1.  Exploring the dataset and traning the model using `Sklearn`.
2.  Building and hosting a `flask`

**About the repository Structure :**

- Project consist `app.py` script which is used to run the application and is engine of this app. is used to predict using the data given by the user in the form
- `model.py` contains code to build and train a Machine learning model.
- in  _templates_  `index.html` is the frontend start page
- in  _templates_  `result.html` is the frontend result page
- in _static_ `style.css` is for styling

### Installation

If you have never ran a machine learning model on you machine then it is recommended to install these dependencies.
open cmd as admin user

```
pip install numpy
```

```
pip install pandas
```

```
pip install -U scikit-learn
```

```
pip install Flask
```

### Run

_To Run the Application_

- first run `model.py` then a pickel file will be created for your model.

```
python model.py
```

- then run `app.py` to deploy you model in the web

```
python app.py
```

- in terminal a address will be generated like `http://127.0.0.1:5000` open it to deploy
