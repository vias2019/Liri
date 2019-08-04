# Liri
________________________________________
ABOUT THE APP
LIRI is a Language Interpretation and Recognition Interface. LIRI is a command line node app that takes in parameters and gives back data. The user has the option of using four commands (listed below):

•	concert-this
•	spotify-this-song
•	movie-this
•	do-what-it-says

Resources used in this project:
1.	Javascript
2.	Nodejs
3.	Node packages:
a.	Node-Spotify-API
b.	Request
c.	Moment
d.	DotEnv
4.	APIs used:
a.	Bands in Town
b.	OMDB

Instructions
1.	Open your terminal (Mac) or Git Bash (PC).
2.	Go to the folder that contains the liri.js file.
3.	Type commands:
__________________________________________________________________________________________
node liri.js concert-this “type name of artist or band in quotes”
Example: node liri.js concert-this “Lady Gaga”
_________________________________________________________________________________

![image](/pictures/concert-this-example.png)

Default output:
![image](/pictures/concert-this-default.png)
 
_____________________________________________________________________________________

node liri.js spotify-this-song <type name of song in quotes>
Example: node liri.js spotify-this-song “Black dog”
_____________________________________________________________________________________
![image](/pictures/spotify-song-example.png)

 
Default output:
![image](/pictures/spotify-song-default.png)
 _____________________________________________________________________________________	

node liri.js movie-this <type name of movie in quotes>
Example: node liri.js movie-this “Gone with the wind”
_____________________________________________________________________________________
![image](/pictures/movie-this-example.png)
 
Default output:
![image](/pictures/movie-this-default.png)
 
_____________________________________________________________________________________

node liri.js do-what-it-says
_____________________________________________________________________________________
 ![image](/pictures/what-says-example.png)
