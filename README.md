# tensorflow-gpu-docker-build
Tensorflow + GPU (CUDA) + Jupyter + Tensorboard

This dockerfile will build tensorflow from sources, check the /tf/Dockerfile for more details, change it if necessary. Based on tensorflow dockerfiles.

## Installation

* install [docker](https://docs.docker.com/install/linux/docker-ce/ubuntu/) (>=19.02)
* install [docker-compose](https://docs.docker.com/compose/install/)
* install [nvidia-docker2](https://github.com/NVIDIA/nvidia-docker)
* clone this repo, build and run the container:

```bash
git clone https://github.com/denisix/tensorflow-gpu-docker-build
cd tensorflow-gpu-docker-build
docker-compose up -d
```

Note: building process can take some time... (on Intel CPU G4400 with SSD and 16G RAM it took ~12 hours)

* check the logs:

`docker-compose logs -f tf`

and open URL in your browser - http://localhost:8888/
