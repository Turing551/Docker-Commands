|      Command      |     Description     |     Usage     |
|      -------      |     -----------     |     -----     |
| `docker -version` | command used to get the currently installed version of docker         |                                     |
| `docker pull`     | command used to pull images from the docker repository(hub.docker.com)| `docker pull <image name>`          |
| `docker run`      | command used to create a container from an image                      | docker run -it -d <image name>      |
| `docker ps`       | command used to list the running containers                           |                                     |
| `docker ps -a`    | command used to show all the running and exited containers            |                                     |
| `docker exec`     | command used to access the running container                          | docker exec -it <container id> bash |
| `docker stop`     | command used to stop the running container                            | docker stop <container id>          |
| `docker kill`     | command used to kill the container by stopping its execution immediately| docker kill <container id>        |
| `docker commit`   | command creates a new image of an edited container on the local system| docker commit <conatainer id> <username/imagename> |
| `docker push`     | command used to push an image to the docker hub repository            | docker push <username/image name>   |
| `docker images`   | command that lists all the locally stored docker images               |                                     |
| `docker rm`       | command used to delete a stopped container                            | docker rm <container id>            |
| `docker rmi`      | command used to delete an image from local storage                    | docker rmi <image-id>               |
| `docker build`    | command used to build an image from a specified docker file           | docker build <path to docker file>  |

