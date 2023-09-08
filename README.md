# MuSHR-ROS-Docker
VSCode Dev Container and Dockerfile for MuSHR Ros Noetic development. Preinstalled with many tools including catkin, python3, conda/mamba, and more.

## Requirments

- Dev Containers plugin for VSCode
- [XQuartz](https://www.xquartz.org/) installed and running (allows GUI elements like matplotlib to display on your mac desktop)
- [Orbstack](https://orbstack.dev/) or [Docker Desktop](https://www.docker.com/products/docker-desktop/) (I have had better luck with orbstack, but that is just me trying to get this to work for an assignment and not testing docker desktop fully)

## Getting Started

1) Open docker desktop
2) Open this repo or another folder with this downloaded .devcontainer from the github repo
3) Inside .devcontainer/Dockerfile rename everything that says "CS4963-Robots" to the name of the root folder of your project.
4) Bottom left of VSCode click the >< icon
5) In the menu that pops up click "Reopen in Container"
- This will build the entire container, this can take a VERY long time
- To View progress click the blue text inside the notification saying "Starting in dev container" or something similar
- Once complete you now are inside the docker container, to open a shell click terminal at the top, then new terminal.
