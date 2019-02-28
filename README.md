# TensorflowCI
This docker-image has TensorFlow as well as TensorFlowJS installed. It can be used to perform various task on your Tensorflow models, e.g. inside any ci-process. It's based on  the original [tensorflow image](https://hub.docker.com/r/tensorflow/tensorflow)

## Versions
We're building this on TensorFlow-version 1.12.0 including Python 3.5

## Build
You can simply trigger a docker-build local by running `docker build . -t demtag/tensorflow-ci` in the cloned repository.

## Contributing
Feel free to contribute and keep this image up to date. You can simply fork our project, improve it and open a pull-request.
