[![Travis](https://img.shields.io/travis/rakshans1/docker-ionic.svg)](https://travis-ci.org/rakshans1/docker-ionic)
[![Pulls](https://img.shields.io/docker/pulls/rakshans1/ionic.svg)]()
[![Layers](https://img.shields.io/imagelayers/layers/rakshans1/ionic/latest.svg)]()
[![Size](https://img.shields.io/imagelayers/image-size/rakshans1/ionic/latest.svg)]()


![rakshans1/ionic](/icon.png?raw=true)
# Latest Ionic 3.18.0
### based on [latest Cordova with the latest Android and the latest Node.js](https://github.com/rakshans1/docker-cordova)
----
### Pull from Docker Hub
```
docker pull rakshans1/ionic:latest
```

### Build from GitHub
```
docker build -t rakshans1/ionic github.com/rakshans1/docker-ionic
```

### Run image
```
docker run -it rakshans1/ionic bash
```

### Use as base image
```Dockerfile
FROM rakshans1/ionic:latest
```