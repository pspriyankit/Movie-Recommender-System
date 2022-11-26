# Movie-Recommender-System

### Overview

The above project is a Movie Recommender System which is a type of content based Recommender System.
It is deployed in heroku environment

Movie recommender system Application URL - https://mrs-priyankit.herokuapp.com/

The `dataset.zip` file contains the two datasets `tmdb_5000_credits` and `tmdb_5000_movies` that are used in this project to build the model

Source of dataset - https://www.kaggle.com/datasets/tmdb/tmdb-movie-metadata

The `requirements` file contains all the necessary prerequiste libraries used in `app.py` file.

The application is build using the streamlit framework you can check out this URL - https://streamlit.io/

The `movie_recommender_system.ipynb` contains the step wise process of Loading , data cleaning , Model building and dumping the results in pickle files

Later the pickle files were used in `app.py` that contains the UI code which was later deployed on the heroku platform for the users utility.

`Procfile` and `setup.sh` contain the configuration details to setup the environment for the deployment on Heroku
