# Predicting Ratings of Reviews RNN

_I carried out this project for my course examination, Deep Learning and Neural Network in my University._

We are tasked with a dataset of an amusement park with visitor's reviews, the dataset contains 6 unique columns and the objective is to study this columns and create a deep neural network model that predicts the rating value of the reviews. "Rating" noted is a column in the dataset. The following text cells will illustrate how I will handle each individual column and build a suitable model to carry out the best possible prediction.
The dataset used is the [Disneyland Reviews dataset](https://www.kaggle.com/datasets/arushchillar/disneyland-reviews), which comprises 42 thousand reviews of 3 Disneyland branches - Paris, California, and Hong Kong, posted by visitors on Trip Advisor.

## Project Overview


1. **Data Analysis/preprocessing:** My preprocessing steps, including handling categorical data (Branch column), transforming rating values into binary classes, and text preprocessing using NLTK, seem appropriate.

2. **Model Architecture:** My model will revolve around a Recurrent Neural Network, In a nutshell I will construct all my experiments of this model with an LSTM( long short-term memory network ) or in consideration its variants, the GRU (Gated recurrent unit)
   
3. **Hyperparameter Tuning:**  I identified key hyperparameters such as the number of hidden layers, dropout rate, learning rate, batch size, activation functions, loss functions, and regularizers. Performing grid search to find optimal values for these hyperparameters is a robust strategy.

4. **Evaluation and Model Selection:** You've planned to evaluate the model's performance using metrics such as accuracy. Grid search cross-validation helps in selecting the best-performing model configuration based on validation scores.


To run my model I used a significant fraction of the entire dataset due to limitation in computational resources, if you have unlimited computation resources, lucky you :)
Enjoy!
