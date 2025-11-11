[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/wojP3-_r)
[![Open in Codespaces](https://classroom.github.com/assets/launch-codespace-2972f46106e565e64193e422d61a12cf1da4916b45550586e14ef0a7c637dd04.svg)](https://classroom.github.com/open-in-codespaces?assignment_repo_id=21217407)
# project-final

Final project repo for INFO 523 - Summer 2025.


## High level goal and expanded description
The goal is to build a music recommender system based on users' listening habits. This algorithm could serve to help listeners to find new music that they might enjoy, and also could help artists by exposing them to listeners that may enjoy their music.


## Research questions
Can we identify distinct groups of artists who are enjoyed by similar listeners?

Can we predict which songs a user is likely to add to their playlist based on their listening history and similar users’ behavior?

    Engineered fields: Song popularity (Number of times a song appears across all playlists) and Collaborative similarity index (Overlap in playlist content between users)

Can we predict whether a song will be added to a playlist , based on the song elements (key, tempo, genre, and loudness) of the songs that already exist in the playlist?


## Data and motivation
This dataset is based on the subset of users in the #nowplaying dataset who publish their #nowplaying tweets via Spotify. In principle, the dataset holds users, their playlists and the tracks contained in these playlists.

User Data Source: https://www.kaggle.com/datasets/andrewmvd/spotify-playlists

Music Metadata Source: https://www.kaggle.com/datasets/devdope/900k-spotify/data

 
## Weekly "plan of attack"
Schedule may be updated as project progresses

10/26 - Decide on project and put together proposal. Initial data exploration and identify research questions.

11/2 - Explore / visualize and understand the data. Summarize the data using histograms and summary tables. Visualize the network of listening habits in a graph.

11/9 - Clean and prepare the data. Remove or replace null values. Identify and remove unnecessary features. Normalize/ standardize the features.

11/16 - Try different algorithms and hyperparameter tuning. For this project both a collaborative filtering and a content filtering approach can be explored. The predictions can be tested by removing songs from users’ playlist, and seeing if the algorithm scored those songs highly for those users.

11/23 - Continue refining algorithms / hyperparameters. Use a hyperparameter tuning framework, and verify that the model is performing as well as possible without overfitting.

11/30 - Refine and validate the model further. Begin to frame project findings into a story corresponding to the research questions.

12/7 - Recap and presentation. Assemble quarto file and visuals. Record the presentation 


## Repository structure and folder `README.md` files
The project repository will be organized into folders like data/, notebooks/, src/, and reports/, each holding the related scripts, notebooks, and documentation. The main README.md will give an overview of the project, setup instructions, and data details to help anyone get started quickly. Each folder will also have its own short README.md explaining what’s inside and how to use it. This structure keeps everything clean, easy to navigate, and ensures the project can be reproduced without confusion.


#### Disclosure:
Derived from the original data viz course by Mine Çetinkaya-Rundel @ Duke University
