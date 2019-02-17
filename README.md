# liri-node-app

## About the App
LIRI is a Language Interpretation and Recognition Interface. LIRI is a command line node app that takes in parameters and gives back data. The user has the option of using four commands (listed below) in conjuntion with specific parameters associated with the commands. The `Commands` are:

* `concert-this`

* `spotify-this-song`

* `movie-this`

* `do-what-it-says`

## How to use LIRI
### Step by Step instructions
1. Open your terminal such as Bash.

2. Navigate to the folder that contains the liri.js file.

3. Depending on the command you run, the output will vary.

#### Example 1: Run `the concert-this` command

 ```node liri.js concert-this <name of artist or band>```
Output: The system will display a list of all events and locations where the artist or band will perform. It can result in multiple records. The system will also log all the results in the log.txt file. 

Here is a Demo:
![Image of concert-this](https://github.com/hagharbi/liri-node-app/blob/master/Screenshots/concert-this%20.gif)

#### Example 2: Run `the spotify-this-song` command

 ```node liri.js spotify-this-song <name of song>```
Output: The system will display a list of information associated with the song. It can result in multiple records. The system will also log all the results in the log.txt file. 

Here is a Demo:
![Image of spotify-this-song](https://github.com/hagharbi/liri-node-app/blob/master/Screenshots/spotify-this-song.gif)

#### Example 3: Run `the movie-this` command

``` node liri.js movie-this <name of movie>```
Output: The system will display information associated with the movie. The system will also log all the results in the log.txt file. 

Here is a Demo:
![Image of movie-this](https://github.com/hagharbi/liri-node-app/blob/master/Screenshots/movie-this.gif)

#### Example 4: Run `the do-what-it-says` command

 ``` node liri.js do-what-it-says```
Output: The system will read the text in the random.txt file, and perform the comman listed in the random.txt file.

Here is a Demo:
![Image of do-what-it-says](https://github.com/hagharbi/liri-node-app/blob/master/Screenshots/do-what-it-says.gif)

## Technology used
* Javascript
* Nodejs
* Node packages:
  * Node-Spotify-API
  * Request
  * Moment
  * DotEnv
* APIs used:
  * Bands in Town
  * OMDB
* Git
* GitHub
