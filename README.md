# docker-compose-spigotmc
A simple docker-compose repository to get a Spigot Minecraft Server up and running effortlessly. 

## Usage

To get started, make sure you have [Docker installed](https://docs.docker.com/docker-for-mac/install/) on your system, and then clone this repository.

## How to use this
Either for when I inadvertently forget or if someone stumbles upon this.

Clone the repository into a folder
```
git clone https://github.com/LewisLarsen/docker-compose-spigotmc.git .
```
Once that has done, the only thing left is to build the container.
```
Build the container to start the server
```
docker-compose up --d --build
```

## Credits & Additional Information
Thank you to [iztg](https://github.com/itzg/docker-minecraft-server) for his image and helpful documentation. For additional reference and advice please see his repository. This is the bare minimum in order to get a Spigot Server working. 
