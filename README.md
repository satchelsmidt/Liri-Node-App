# Liri-Node-App
LIRI is a Language Interpretation and Recognition Interface. This is a command line node app that takes in parameters and gives you back data from three separate APIs -- OMDB, BandsinTown, and Spotify.

# 
*Clearly state the problem the app is trying to solve (i.e. what is it doing and why):*
    This app is designed to allow users to search for and retrieve information on their favorie bands, songs, and movies 

Give a high-level overview of how the app is organized
    The app is organized into multiple js files (modularized). The bulk of the app is in the liri.js file, which contains the functions that make the axios calls and return values based on user input. The 


Give start-to-finish instructions on how to run the app
    The user opens the terminal in the correct filepath (the liri.js file), and from there they can type in node liri.js, followed by one of four commands:

concert-this "band/artist name": this will return a list of concert dates/locations for the input band/artist

spotify-this-song "song name": this willreturn the song artist, name, snippet, and album from spotify

movie-this "movie name": this will return movie information on a specific movie to the user (title, year, imdb/rt rating, country produced, language, plot, and actors)

do-what-it-says: this will run the spotify search for "I want it that way" 

Include screenshots, gifs or videos of the app functioning

Gif 1:
<img src="/assets/gif_1.gif" width="40" height="40" />

Gif 2:
<img src="/assets/gif_2.gif" width="40" height="40" />

Gif 3:
<img src="/assets/gif_3.gif" width="40" height="40" />

Gif 4:
<img src="/assets/gif_4.gif" width="40" height="40" />

Contain a link to a deployed version of the app


Clearly list the technologies used in the app
Axios -- method of getting/posting api calls using https
Javascript -- language used to code
node.Js -- command line interface where code runs
Spotify APi -- returns a large amount of song data
OMDB API -- returns a large amount of movie data
Bands in Town API -- returns detailed info on various bands/artists concert dates

State your role in the app development
I developed it