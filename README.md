# SoloLa python3.5 Docker Image

> <span class="highlight">Caution! This version of soloLa is unstable</span>

We provide an docker image for SoloLa python3.5 . Check out the image on Docker Hub

> https://hub.docker.com/r/ykhorizon/solola-py35/

(This dockerfile and image are prepared for soloLa-core and solaLa platfrom development)


## System Version

We use essentia docker image as base images:

- ubuntu:16.04 (latest ubuntu LTS)

Other dependency check out [SoloLa Requirements](https://github.com/SoloLa-Platform/SoloLa/tree/dev_version)


## Usage for Developer

<pre> 
docker run -ti --rm -v `pwd`:/soloLa ykhorizon/solola-py35 bash bash 
git clone https://github.com/SoloLa-Platform/SoloLa.git
cd SoloLa
git checkout dev_version
sh test.sh
</pre>

