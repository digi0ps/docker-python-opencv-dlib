# Python OpenCV Dlib Docker Image

Docker Image with Python 3.6, OpenCV 3.3.0 and Dlib 19.16.
Based off my other docker image, [python-opencv](https://github.com/digi0ps/docker-python-opencv).

## Running it
```
docker run -it digi0ps/python-opencv
>>> import cv2
>>> import dlib
```

## Using as Base
```
FROM digi0ps/python-opencv-dlib
RUN ...
```

## Tags
- `latest`

## TODO
- [ ] Use alpine.
- [ ] Reduce final image size.