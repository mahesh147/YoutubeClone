# YoutubeClone

A Youtube clone with minimal features implemented using the Youtube Data API 3.


## How to set it up and test it out in the browser

 - Download .zip of the repo or clone it.
 - Install all the dependecies. Run 'yarn install' or 'npm install'. This can take a while.
 - Once all the dependecies are installed run - 'npm start' to spin up the local dev server.

## API key setup

The API key has been excluded from this public repo. You'll need to get your own API key in order for the web-app to work. Head over to https://console.developers.google.com to signup for an API key. Make sure you get the YouTube Data API v3. 
Once you have the API key add the following line to YoutubeClone/src/index.js :
	
	const API_KEY = '[YOUR API KEY GOES HERE]';

Save the file and run - 'npm start' in the console.
