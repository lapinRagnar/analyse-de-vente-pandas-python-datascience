# Analyse de Données vente pandas - python datascience

### les choses à faire
We start by cleaning our data. Tasks during this section include:

Drop NaN values from DataFrame
Removing rows based on a condition
Change the type of columns (to_numeric, to_datetime, astype)
Once we have cleaned up our data a bit, we move the data exploration section. In this section we explore 5 high level business questions related to our data:

What was the best month for sales? How much was earned that month?
What city sold the most product?
What time should we display advertisemens to maximize the likelihood of customer’s buying product?
What products are most often sold together?
What product sold the most? Why do you think it sold the most?
To answer these questions we walk through many different pandas & matplotlib methods. They include:

Concatenating multiple csvs together to create a new DataFrame (pd.concat)
Adding columns
Parsing cells as strings to make new columns (.str)
Using the .apply() method
Using groupby to perform aggregate analysis
Plotting bar charts and lines graphs to visualize our results
Labeling our graphs


# setup
### installer le venv sous windows
```
python -m venv env
env\Scripts\activate
pip freeze > requirements.txt
```

### installation des librairies
```
pip install pandas
pip install "pandas[excel]"
python -m pip install -U matplotlib
```



# les commandes
z

# le tuto
https://www.youtube.com/watch?v=eMOA1pPVUc4

# les ressources
https://pandas.pydata.org/docs/getting_started/install.html

