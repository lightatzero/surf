# Surf

A docker based web grazer that monitors webpages.

# Dependencies

* [Docker](https://docs.docker.com/engine/install/) - Get this on your machine
* [ubuntu-vnc-desktop](https://github.com/fcwu/docker-ubuntu-vnc-desktop) - Creat a box to graze in

# Inital work 

```sh
$ docker create -p 6080:80 --name surfer -v /dev/shm:/dev/shm dorowu/ubuntu-desktop-lxde-vnc
$ docker start surfer
```

Then open [http://127.0.0.1:6080/](http://127.0.0.1:6080/) in a browser

