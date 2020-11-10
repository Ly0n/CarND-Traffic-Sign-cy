# Deep Learning Traffic Sign Detection Project   

## Run

## Install Docker 

Follow this tutorial to install Docker on Ubuntu 18.04:
https://www.digitalocean.com/community/tutorials/how-to-install-and-use-docker-on-ubuntu-18-04

## Clone Repo

```
git clone https://github.com/Ly0n/CarND-Traffic-Sign-cy
cd CarND-Traffic-Sign-cy
```

## Run Docker Container with all the pre-installed environment 

```
docker run --interactive --tty --rm --publish 8888:8888 --volume $PWD:/src udacity/carnd-term1-starter-kit:latest
```

## Run Jupyter Notebook

Open your Browser and enter the URL printed by the docker command:

```
http://127.0.0.1:8888/?token=<your_token>
```
