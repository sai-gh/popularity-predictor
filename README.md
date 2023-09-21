Song Popularity Prediction Project Flowchart

                       ┌───────────────────────┐
                       │ Download 'dataset.csv'│
                       └────────────┬──────────┘
                                    │
                                    v
                   ┌────────────────────────────────────────┐
                   │ 'song_popularity_prediction_pre_model' │
                   └────────────────┬───────────────────────┘
                                    │
                                    v
           ┌─────────────────────┐    ┌───────────────────────┐
           │   EDA and Data      │    │   Data Cleaning and   │
           │   Exploration       │    │   Preprocessing       │
           └─────────────────────┘    └───────────────────────┘
                                    │
                                    v
                 ┌───────────────────────────────────────────┐
                 │   'song_popularity_prediction_modeling'   │
                 └──────────────────┬────────────────────────┘
                                    │
                                    v
                       ┌───────────────────────┐
                       │  Feature Engineering  │
                       │     and Selection     │
                       └────────────┬──────────┘
                                    │
                                    v
       ┌──────────────────────┐        ┌───────────────────────┐
       │ Build Multiple       │        │ Refine and Perform    │
       │ Baseline Models      │        │ Hyperparameter        │
       └──────────────────────┘        │ Tuning on Best        │
                                       │ Performing Models     │
                                       └───────────────────────┘
                                    │
                                    v
                       ┌───────────────────────┐
                       │ Final Model Selection │
                       └────────────┬──────────┘
                                    │
                                    v
                       ┌───────────────────────┐
                       │ Prediction Results    │
                       └────────────┬──────────┘
                                    │
                                    v
                       ┌───────────────────────┐
                       │ Conclusion and        │
                       │ Future Directions     │
                       └───────────────────────┘

## Song Popularity Prediction

Welcome to the **Song Popularity Prediction** project! This project is focused on building a machine-learning model to predict the popularity of songs based on various features available in the Spotify dataset.

## Project Structure

The project is divided into two Jupyter Notebooks:

1. **[song_popularity_prediction_pre_model.ipynb](https://github.com/sai-gh/popularity-predictor/blob/main/song_popularity_prediction_pre_model.ipynb)**:
   In this notebook, you will find the Exploratory Data Analysis (EDA) and data cleaning process. We analyze the dataset to gain insights into its structure and distribution, perform data cleaning, and preprocess the data to handle missing values and convert categorical features. Additionally, we visualize the relationships between features and the target variable 'popularity' to understand their impact on the prediction.

2. **[song_popularity_prediction_modeling.ipynb](https://github.com/sai-gh/popularity-predictor/blob/main/song_popularity_prediction_modeling.ipynb)**:
   This notebook focuses on the modeling process. We start with feature engineering and selection to identify the most relevant features for our popularity prediction model. Then, we build multiple baseline models to understand their performance. After evaluating the baseline models, we refine and perform hyperparameter tuning on the best-performing models to achieve the highest accuracy and precision. We also discuss the importance of precision in song popularity prediction and how it benefits the music industry.

## Dataset

To run the notebooks successfully, you need to download the **[dataset.csv](https://github.com/sai-gh/popularity-predictor/blob/main/dataset.csv)** file. This dataset contains various features of songs from Spotify, including acousticness, danceability, energy, instrumentalness, liveness, loudness, speechiness, tempo, and valence, among others. The target variable 'popularity' represents the popularity score of each song.

## Note

- Please ensure that you have the required Python libraries and dependencies installed (specified in `[requirements.txt](https://github.com/sai-gh/popularity-predictor/blob/main/requirment.txt)`).
- Run the notebooks in the given order ('song_popularity_prediction_pre_model' first, then 'song_popularity_prediction_modeling') to follow the project flow.

Happy predicting, and enjoy exploring the world of song popularity!

