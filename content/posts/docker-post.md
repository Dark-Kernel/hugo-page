---
title : "Docker"
date: 2022-07-07
draft: false
featured_image: "/docker-logo.png"
---


## Docker 


Docker is an open source containerization platform. It
enables developers to package applications into containers—standardized
executable components combining application source code with the
operating system (OS) libraries and dependencies required to run 
that code in any environment. Containers simplify delivery of
distributed applications, and have become increasingly popular 
as organizations shift to cloud-native development and hybrid 
multicloud environments.


![DockerLogo](/docker-logo.png)


Containers are made possible by process isolation and virtualization 
capabilities built into the Linux kernel.

## Installation 

~ Arch

`yay -S docker-git`

~ Debian

`sudo apt install docker.io`

OR

visit https://download.docker.com/linux/debian/dists/
choose your version, browse to pool/stable/ choose your architecture
Download .deb file

`sudo dpkg -i path/to/installed-file.deb`



## Error fixing

After Installation if you face soms problem like below: 

     tcp://localhost:2375/usr/lib/systemd/system/docker.socket.
     Is the docker daemon running?

**Then here is the solution :**

 1.Add your self to the docker group

    `usermod -aG docker $USER`

 2.Fix permissions on docker socker and command.

    `sudo chgrp docker /usr/bin/docker`
    `sudo chgrp docker /var/run/docker.sock`

     ~$ ll $(which docker)
        -rwxr-xr-x 1 root docker 18991768 08.07.2017 22:57 /usr/bin/docker*

     ~$ ll /var/run/docker.sock
        srw-rw---- 1 root docker 0 23.07.2017 10:21 /var/run/docker.sock

 3.Add variables to config environment for docker command

    `export DOCKER_HOST=unix:///var/run/docker.sock`

 4.Rest Docker

    `sudo systemctl restart docker`


This should fix the error.



## Run

Lets run the hello-world:
  
	 sudo docker run hello-world


1.Let's pull our first OS

	docker pull centos

  >*You can pull any other os or any available software also from docker hub*



2.run it 

	docker run -d -t --name <name> centos

3.check our container is running or not

	docker ps

4.Get into container

	docker exec -it <name> <shell>

Now you will be on your centos.


<br>

**Thanks for reading.**
