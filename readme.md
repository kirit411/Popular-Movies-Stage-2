# This project is created by Kirit Bhatt for the Udacity Nanodegree program
    This is the third project which is continuation of Popular Movies Stage 1
##vPopular Movies, Stage 1
Build a simple movies app that communicates with the internet and provides a responsive user experience. 
In this project, you’ll fetch data from the Internet with the MovieDB API, use adapters and custom list 
layouts to populate list views, and incorporate libraries to simplify your code.

## Popular Movies, Stage 2
Expand on the movies app you built in Project 1 to create a fully-featured app. In this project, you’ll
allow users to view and play trailers, read reviews, and mark their favorite movies. You’ll also 
create a database and content provider to store and handle your app data.
    
## Project Highlights
In this project, we continue building the movies app, which will:
- Show a list of available trailers for each movie.
- Launch Youtube link for trailer when clicked.
- Show a list of reviews for each movie if available.
- Allow user to favorite a movie by toggling a favorite icon.
- Allow filtering by favorite movies in the main list, in addition to sorting by most popular and top-rated.
- Save favorite movies in database using Android Architecture Components:
  - Room to read and write to database
  - Live Data to observe changes in database
  - Model View to cache Live Data to minimize database queries, e.g. when rotating.

## Data Source and Instructions:
All movie data used in this project are obtained from [themoviedb.org API](https://www.themoviedb.org/documentation/api)
Please register your with themoviedb.org and obtain your own API key.
Please replace api key for theMovieDB API in [`app/src/main/res/values/apikey.xml`]
