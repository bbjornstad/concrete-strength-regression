# Concrete Strength Regression
In this project, we will predict the concrete compressive strength using regression techniques. This is a measure of the ability of concrete to withstand compression, and is a nonlinear relationship of both the age of the concrete and the ingredients used to create the concrete. This dataset comes directly from [Kaggle](https://www.kaggle.com/maajdl/yeh-concret-data/).

## Project Implementation
This project is implemented using Python, Jupyter Notebooks, and associated tools from Data Science, most importantly scikit-learn. This library makes implementations of many common machine learning algorithms quite simple and allows for easy parameter tuning to find the best models.

## The Data
The data is given with the following features:
- Cement (component 1) -- quantitative -- kg in a m3 mixture -- Input Variable
- Blast Furnace Slag (component 2) -- quantitative -- kg in a m3 mixture -- Input Variable
- Fly Ash (component 3) -- quantitative -- kg in a m3 mixture -- Input Variable
- Water (component 4) -- quantitative -- kg in a m3 mixture -- Input Variable
- Superplasticizer (component 5) -- quantitative -- kg in a m3 mixture -- Input Variable
- Coarse Aggregate (component 6) -- quantitative -- kg in a m3 mixture -- Input Variable
- Fine Aggregate (component 7) -- quantitative -- kg in a m3 mixture -- Input Variable
- Age -- quantitative -- Day (1~365) -- Input Variable

The data has the following as an output variable:
- Concrete compressive strength -- quantitative -- MPa -- Output Variable

## Project Structure
- The [main notebook file](index.ipynb) is the place to view a technical analysis and visualizations.
- The [`data`](./data/) folder contains the dataset as a CSV file.
