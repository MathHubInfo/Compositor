# Compositor

A small Docker Container used to compose the different containers used by MathHub. 

It runs an NGINX server, that delegates to:
* [the Frontend](https://github.com/MathHubInfo/Frontend)
* [the Admin Interface](https://github.com/MathHubInfo/Admin)
* [Portainer](https://github.com/MathHubI)
* [the Backend](https://github.com/Uniformal/MMT)

NGINX listens on port 80, and is available as the automated build [mathhub/compositor](https://hub.docker.com/r/mathhub/compositor/) on DockerHub. 

## License

Licensed under AGPL 3.0. 