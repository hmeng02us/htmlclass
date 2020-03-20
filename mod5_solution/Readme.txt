Because this solution calls other snippet and js, it violates the CORS requirement if run locally as file.

This need to be run either with a local host server(like MAMP), or uploaded to Github and run as a true webpage.

Funny thing is, Github can not host php, to do that need to use localhost server for local testing, and add ngrok for temporary tunnel used in remote testing.