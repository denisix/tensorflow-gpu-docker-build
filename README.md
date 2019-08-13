# tensorflow-gpu-docker-build
Tensorflow + GPU (CUDA) + Jupyter + Tensorboard

This dockerfile will build tensorflow from sources, check the /tf/Dockerfile for more details, change it if necessary. Based on tensorflow dockerfiles.

Prior to 
Installation

* install docker-compose, docker >= 19.02, from official sources
* install nvidia-docker2, check detailed instructions here - https://github.com/NVIDIA/nvidia-docker
* clone the repo:

`git clone https://github.com/denisix/tensorflow-gpu-docker-build`
* build and run it:

`docker-compose up -d`
