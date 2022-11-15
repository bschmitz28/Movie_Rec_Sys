# Movie_Rec_Sys

Project name: Movie Recommendation System
Methods used for the project: K-Means Clustering & Collaborative Filtering.

Description: K-Means clustering was used to find different groups of users based on the rating scores and genres from movie dataset. Collaborative Filtering was used to find the similarity between user to an active user to predict a rating score for an unseen movie.

Software Requirenment:<br />
-Anaconda (Jupyter Notebook)<br />
-Python3

Import these libraries like so as shown below:<br />

import pandas as pd<br />
import numpy as np<br />
import matplotlib.pyplot as plt<br />
import seaborn as sns<br />
from sklearn.neighbors import NearestNeighbors<br />
from sklearn.decomposition import PCA<br />
from sklearn.cluster import KMeans<br />
from mpl_toolkits.mplot3d import Axes3D<br />
from sklearn.metrics import mean_squared_error<br />
import math<br />
from wordcloud import WordCloud<br />

1.Clone the repo<br />
2.Open Anaconda Navigator<br />
3.Open Jupyter Note<br />
4.Go to the folder contains the files<br />
5.Open Movie Rec Sys.ipynb<br />
6.Click on "Restart the kernel, then re-run the whole notebook"<br />

The beginning is importing the data, cleaning the data, and exploratory data analysis. Lines
Two main functions in the notebook can be found at line 116 and 149.

*The function final_recommendation_system(userId) is used for getting a list of recommended movies to a user with the input is userId (int).<br />
*The function predict_rating(id_user, movieId) is used for getting a predicted rating score for an unseen movie with the input userId(int) and movieId(int).
