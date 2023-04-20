To run the frontend of the game is required Docker.
Here is the [official guide](https://docs.docker.com/engine/) for installing Docker.

How to run the Docker container:
1. Open a Terminal inside the "sec-game_demo" folder
2. Build the Docker folder ```docker build --tag sec-game_demo ./```
3. Start the Docker Container ```docker-compose up```
4. Enter the frontend using a browser and the link [http://localhost:8080](http://localhost:8080)
NOTE: the terminal where ```docker-compose up``` was issued has to remain open idle

To stop the container:
1. Enter the Terminal where the command ```docker-compose up``` was issued
2. Click ```ctrl + c``` and wait for the docker to stop
3. Enter the command ```docker-compose down``` to completely remove the Docker