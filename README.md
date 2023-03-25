# tensorflow-gpu-jupyterlab

## Summary
Couldn't find any working examples of this:
- tensorflow-gpu
- jupyterlab
- jupyter password & token disabled
- using docker-compose
- nvidia gpu accessible

So, this docker-compose has all the above working. Tested on ubuntu 22.04 LTS. 

## Usage
1. Install nvidia drivers for your machine
2. Install nvidia docker: https://github.com/NVIDIA/nvidia-docker
3. Clone this repo
4. cd to this directory and `docker-compose up -d`
