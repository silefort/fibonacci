# Create the client app

    $ npm install -g create-react-app
    $ create-react-app client

# Production Multi-Container Deployments

* Push cod to github
* Travis automatically pulls repo
* Travis builds a test image tests code
* Travis builds prod images
* Travis pushes built prod images to Docker Hub
* Travis Pushes project to AWS EB
* EB pulls images from Docker Hub, deploys
