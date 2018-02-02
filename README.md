# Tensorflow:
#### Make tensorflow docker images from Dockerfile.GPU and Dockerfile.CPU. The GPU version already includ opencv 3.4. and python 3.5 . The base image is cuda:8.0-cudnn7-runtime-ubuntu16.04.

# The docker registry is :
https://hub.docker.com/r/jermine/tensorflow/

# Used

## Checked nvidia driver info
```
docker run --runtime=nvidia --rm -it jermine/tensorflow:gpu nvidia-smi
```
## Get pip3 list
```
docker run --rm -it jermine/tensorflow:gpu pip3 list
```
