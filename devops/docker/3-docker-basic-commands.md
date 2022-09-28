# Docker Commands

**Content**

1\. Docker Commands

2\. References

## 1. Docker Commands

-   Some of the basic docker commands are listed below
1.  docker –version
2.  docker pull
3.  docker run
4.  docker ps
5.  docker ps -a
6.  docker exec
7.  docker stop
8.  docker kill
9.  docker images
10. docker rm
11. docker rmi
12. docker build
13. docker commit
14. docker login
15. docker push

## 1.1 docker –version

-   This command is used to get the currently installed version of docker.

    ![](media/e1d6b5d31ef031d4134cc2e5a3cc8ad8.png)

## 1.2 docker pull

-   This command is used to pull images from the **docker repository**(hub.docker.com).

    **Usage: docker pull \<image name\>**

![](media/76915f4e5ff3db3eabc16a3b5fcd8e7b.png)

## 1.3 docker run

-   This command is used to create a container from an image.

    **Usage: docker run -it -d \<image name\>**

![](media/4f6011d08bf8ea0dba30e1f89c2e6f18.png)

## 1.4 docker ps

-   This command is used to list the running containers.

![](media/2797d835567bb41bd1d62560dfcb51d4.png)

## 1.5 docker ps -a

-   This command is used to show all the running and exited containers.

![](media/00069359c12f1603873466db644cab60.png)

## 1.6 docker exec

-   This command is used to access the running container.

    **Usage: docker exec -it \<container id\> bash**

![](media/37e40b71d3d88570807da17e10c63d52.png)

## 1.7 docker stop

-   This command stops a running container.

    **Usage: docker stop \<container id\>**

![](media/2e18c4d044100c92cf7fd93a89f57600.png)

## 1.8 docker kill

-   This command kills the container by stopping its execution immediately.
-   The difference between ‘docker kill’ and ‘docker stop’ is that ‘docker stop’ gives the container time to shutdown gracefully, in situations when it is taking too much time for getting the container to stop, one can option to kill it.

    **Usage: docker kill \<container id\>**

![](media/f98af6771722160b3ec834b97bbd2891.png)

## 1.9 docker images

-   This command lists all the locally stored docker images.

![](media/28dffe53c4709d87b5eb6eca7bb8944d.png)

## 1.10 docker rm

-   This command is used to delete a stopped container.

    **Usage: docker rm \<container id\>**

![](media/6575c85c731445701e8ac09e9a7bf66f.png)

## 1.11 docker rmi

-   This command is used to delete an image from local storage.

    **Usage: docker rmi \<image-id\>**

![](media/0bce6bbaecb92e3a9f5f0c72d86d8ea5.png)

## 1.12 docker build

-   This command is used to build an image from a specified docker file.

    **Usage: docker build \<path to docker file\>**

![](media/aa4c43a090ec3badb18d75261b9072a7.png)

## 1.13 docker commit

-   This command creates a new image of an edited container on the local system.

    **Usage: docker commit \<conatainer id\> \<username/imagename\>**

![](media/a3193ee1d6d8bbf476d00494f965e940.png)

## 1.14 docker login

-   This command is used to login to the docker hub repository.

![](media/cbd93327fb74a288672ac2e5a9663edb.png)

## 1.15 docker push

-   This command is used to push an image to the docker hub repository.

**Usage: docker push \<username/image name\>**

![](media/17b5c3948e6dd3d5a1bf9ba22a64efdf.png)

## 2. References

1.  https://www.edureka.co/blog/docker-commands/
