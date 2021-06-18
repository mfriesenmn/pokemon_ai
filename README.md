# pokemon_ai
Group Project for UMN Boot Camp, Spring 2021 to use machine learning predict typology of fictional pokemon or theoretical pokemon.
Group Members: Tanner Riebel, Mason Totall, Daniel Bernal, Michael Friesen

## Our Question
We were curious to see if machine learning could be used to determine the Legendary status or the Type of a Pokemon using their stats alone. We decided to use 4 different models of machine learning to test our question:

* Neural Networks
* K Nearest Neighbors (KNN)
* Random Forest
* Support Vector Machine (SVM)

## Dataset
Our dataset was retrieved from Kaggle (https://www.kaggle.com/abcsds/pokemon) and contains information on 800 Pokemon, including Legendary Status, Pokemon Type (Primary & Secondary) and several supporting stats (Health Points, Attack, Defense, etc.) We did minimal re-formatting to be able to use the dataset, and have included it as a CSV in this repository.

## Analysis
To examine our analysis:

1. Activate your Python Environment and open Jupyter Notebooks.
1. Open the notebook labeled "models.ipynb".
1. Run the first cell to import dependencies and load the dataset.
1. Run the next cell to create 50 models for predicting a Pokemon's Type by their stats. NOTE: This may take quite a long time on your machine depending on your specific set-up. Change the range of the iterations to a smaller number than 50 to run shorter.
1. Run the next cell to generate a box-and-whisker plot of the models to compare accuracies for Type.
1. Run the next cell to generate prediction data for all 800 pokemon (Note that this will include the training and testing sets).
1. Run the next cell to create 50 models for predicting a Pokemon's Legendary Status by their stats. NOTE: This may take quite a long time on your machine depending on your specific set-up. Change the range of the iterations to a smaller number than 50 to run shorter.
1. Run the next cell to generate a box-and-whisker plot of the models to compare accuracies for Legendary Status.


## Results
To view our interpretation of the results of comparing these 4 models, you can find our data on display at https://mfriesenmn.github.io/pokemon_ai/index.html.
