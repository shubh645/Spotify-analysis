# Spotify Data Analysis
This project is a data analysis of a Spotify dataset, exploring user listening habits and track information. The analysis is performed in a Jupyter notebook (Spotify.ipynb) using Python and various data science libraries.

## Project Overview
* The project aims to provide insights into a user's Spotify listening activity. The analysis includes:
* Data Loading and Cleaning: The notebook loads a dataset from a CSV file, then cleans the data by removing duplicate entries and handling missing values.
* Descriptive Statistics: It provides a descriptive summary of the dataset to understand the overall distribution and characteristics of the data.
* User Analysis: The notebook identifies the top 5 most active users based on the time they spent listening to music.
* Artist and Album Analysis: It counts the number of unique artists and albums, and identifies the top 10 most common artists and albums in the dataset.
* Platform and Behavior Analysis: It provides a breakdown of users by their platform and analyzes the reasons why users start and stop listening to tracks.

## Technologies Used
* Python: The core programming language for the analysis.
* Pandas: Used for data manipulation, cleaning, and analysis.
* Seaborn & Matplotlib: Used for creating data visualizations (although specific visualizations were not shown, the libraries were imported, indicating their intended use).
* Jupyter Notebook: The interactive environment where the analysis is performed and presented.

## Dataset
The analysis is based on a dataset that contains 149,860 entries and 12 columns. The key columns include:
* User_no: Unique user identifier.
* Timestream: Timestamp of the listening activity.
* Platform: The platform used for listening (e.g., Android, iOS).
* MLsec_played: The number of milliseconds the track was played.
* Track_name: The name of the song.
* Artist_name: The name of the artist.
* Album_name: The name of the album.
* Reason_start & Reason_end: Reasons for starting and ending a track.
* Shuffle: Whether shuffle mode was on or off.
* Skipped: Whether the track was skipped.

## Getting Started
Clone this repository to your local machine.
* Ensure you have the required libraries installed (pandas, seaborn, and matplotlib).
* If not, you can install them using pip:
* pip install pandas seaborn matplotlib
* Open the Spotify.ipynb file in a Jupyter Notebook environment (e.g., Jupyter, VS Code with the Jupyter extension).

Run the cells in the notebook to replicate the analysis.
