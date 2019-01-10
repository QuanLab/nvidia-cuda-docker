# NVIDIA Cuda Dockerfile

## Introduction
This repository provides Dockerfile to build docker image for Running Machine Learning Algorithm with multi-GPUs supported.

## How to build
These examples, along with our NVIDIA deep learning software stack, are provided in a monthly updated Docker container on the NGC container registry (https://ngc.nvidia.com). These containers include:  

docker run --runtime=nvidia -e NVIDIA_VISIBLE_DEVICES=all -e OPENBLAS_NUM_THREADS=1 -it --mount type=bind,source=/home/quanpv/data,target=/data quanpv/cuda-base:1.0.8

## NVIDIA support
In each of the network READMEs, we indicate the level of support that will be provided. The range is from ongoing updates and improvements to a point-in-time release for thought leadership.

## Feedback / Contributions
We're posting these examples on GitHub to better support the community, facilitate feedback, as well as collect and implement contributions using GitHub Issues and pull requests. We welcome all contributions!

## Known issues
In each of the network READMEs, we indicate any known issues and encourage the community to provide feedback.
