# Simple python flask docker hello world
This repository contains a very simple hello world for a docker container with a running flask application.

***
## How to
 
Build the image with following command:
```bash
docker build . -t py_flask_helloworld:latest
```

Run the container using this command :
```bash
docker run -dp 3000:3000 py_flask_helloworld:latest
```

To see the application go to your browser and open `localhost:3000`
