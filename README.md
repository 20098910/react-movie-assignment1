# Assignment 1 - ReactJS app.

Name: Shane

## Overview.

This is a react website which uses the movie database to return a list of movies including their relevant information

### Features.
 
+ Added a popular movies page to view some of the most liked movies (static end-point)
+ Added a top rated page to show some of the highest rated movies (static end-point)
+ Added a now playing page to show some of the newest movies for watching (static end-point)
+ Added movie credits to show the Actors in the movie ( and the character they played) and the crew who worked on the movie (parameterised end-point)
+ update the colour scheme for each page.
+ Created a table to display the cast and crew of the movie (This is responsive)

## Setup requirements.

+ Download the .zip file of the repository by clicking on "Code"
+ Extract the contents of the file in your downloads folder
+ Open the IDE of your choice and selec the folder to open it

+ To run the program, use the command line in the IDE to navigate to the /movies directory

  ```
  cd movies
  ```

+ Next, use the follow code to start the program

  ```
  npm start
  ```
  
## API endpoints.

+ Top rated Movies - movies/topRated
+ Movies now Playing - movies/nowPlaying
+ Popular Movies - movies/popular
+ Movie Credits - credits/:id

## Routing.

+ credits/:id - MovieCreditsPage
+ movies/topRated - TopRatedPage
+ movies/nowPlaying - NowPlayingPage
+ movies/popular - PopularPage

