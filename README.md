# liri-node-app

The liri bot is a CLI (Command Line Interface) app that uses several node modules and api's to receive commands and output the API responses to the terminal. The app receives commands in a command value format.

# Notes
The following commands are the only valid commands for the app:
- concert-this
  - takes an artist name and returnes upcoming concert information
- spotify-this-song
  - takes a song title and returns artist and album information
- movie-this
  - takes a movie title and returns movie information
- do-what-it-says
  - this command allows for the user to pass the one of the other commands and a value into the app from the random.txt file.
  
The log.txt file records all succesfull runs of the liri bot app.

# Languages/API's/Concepts Used
- JavaScript
- Node
- NPM
- Moment JS
- Require JS
- Spotify API
- BandsinTown API

# Future Enhancements

A future enhancement would be the app logging the errors to the log.txt file as well. This would provide a more complete and realistic application.

# Acknowledgments

Big shout out to [PurpleBooth](https://gist.github.com/PurpleBooth/109311bb0361f32d87a2) for posting this Read Me template on github!
