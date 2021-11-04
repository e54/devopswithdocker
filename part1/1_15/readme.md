# Super simple dockerized C app "simple"

Tried to find out how the image and the container can be done so they take a minimal amount of space. The end result is an image that's around 5 megabytes large.

To execute the app, run the following commands in CLI:
```
docker pull esakorte/simple
docker run esakorte/simple
```
The app should output "I am the simplest of them all".
