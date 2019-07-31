# Linear Regression Quiz: 

## Getting Started 

In this quiz, you'll be working with data on the average life expectancy at birth and the average BMI for males across the world. 

### Install

This project requires **Python 3.7** and the following Python libraries installed:

- [NumPy](http://www.numpy.org/)
- [Pandas](http://pandas.pydata.org)
- [matplotlib](http://matplotlib.org/)
- [scikit-learn](http://scikit-learn.org/stable/)

You will also need to have software installed to run and execute an [iPython Notebook](http://ipython.org/notebook.html)

We recommend students install [Anaconda](https://www.continuum.io/downloads), a pre-packaged Python distribution that contains all of the necessary libraries and software for this project. 

### Code

Template code is provided in the `life_expectancy_prediction.ipynb` notebook file. You are required to use the `bmi_and_life_expectancy.csv` dataset file to complete your work. 

### Dataset 
The data comes from [Gapminder](https://www.gapminder.org/). The dataset file can be is `bmi_and_life_expectancy.csv`. It includes three columns, containing the following data:

- `Country`: The country the person was born in.
- `Life expectancy`: The average life expectancy at birth for a person in that country.
- `BMI`: The mean BMI of males in that country.

### You'll need to complete each of the following steps: 

`Step 1`: **Load the dataset**

- The dataset is in the file called `bmi_and_life_expectancy.csv`.
- Use pandas **`read_csv`** to load the data into a dataframe (don't forget to import pandas!)
- Assign the dataframe to the variable `bmi_life_data`.

`Step 2`: **Build a linear regression model**

- Create a regression model using scikit-learn's **`LinearRegression`** and assign it to `bmi_life_model`.
- Fit the model to the data.

`Step 3`: **Predict using the model**
- Predict using a BMI of 21.07931 and assign it to the variable `laos_life_exp`.

### Run

In a terminal or command window, navigate to the top-level project directory `finding_donors/` (that contains this README) and run one of the following commands:

```bash
ipython notebook finding_donors.ipynb
```  
or
```bash
jupyter notebook finding_donors.ipynb
```

This will open the iPython Notebook software and project file in your browser.
