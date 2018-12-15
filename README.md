# Sentinel Docker

This project contains a Docker image meant to facilitate the deployment of [Sentinel](https://github.com/alibaba/Sentinel) 


[Dcoker Hub address](https://cloud.docker.com/repository/docker/huangjing/sentinel)

## Project directory

* build：Sentinel makes the source code of the docker image
* example: Docker compose example for Sentinel dashboard

## Quick Start

Run the following command：

* Clone project

  ```powershell
  git clone https://github.com/SKYhuangjing/sentinel-docker.git
  cd sentinel-docker
  ```


* RUN

  ```powershell
  docker-compose -f example/docker-compose.yml up
  ```

* Open the Sentinel dashboard in your browser

  link：http://127.0.0.1:38080