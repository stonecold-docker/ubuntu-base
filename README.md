# ubuntu-base
![Docker Pulls](https://img.shields.io/docker/pulls/forumi0721/ubuntu-base)
![Docker Stars](https://img.shields.io/docker/stars/forumi0721/ubuntu-base)



----------------------------------------
### x64
![Docker Image Version](https://img.shields.io/docker/v/forumi0721/ubuntu-base/latest)
![Docker Image Size](https://img.shields.io/docker/image-size/forumi0721/ubuntu-base/latest)
### aarch64
![Docker Image Version](https://img.shields.io/docker/v/forumi0721/ubuntu-base/aarch64)
![Docker Image Size](https://img.shields.io/docker/image-size/forumi0721/ubuntu-base/aarch64)
### x64_focal
![Docker Image Version](https://img.shields.io/docker/v/forumi0721/ubuntu-base/x64focal)
![Docker Image Size](https://img.shields.io/docker/image-size/forumi0721/ubuntu-base/x64focal)
### x64_bionic
![Docker Image Version](https://img.shields.io/docker/v/forumi0721/ubuntu-base/x64bionic)
![Docker Image Size](https://img.shields.io/docker/image-size/forumi0721/ubuntu-base/x64bionic)
### x64_xenial
![Docker Image Version](https://img.shields.io/docker/v/forumi0721/ubuntu-base/x64xenial)
![Docker Image Size](https://img.shields.io/docker/image-size/forumi0721/ubuntu-base/x64xenial)



----------------------------------------
#### Description

* Distribution : [Ubuntu](https://www.ubuntu.com/)
* Architecture : x64,aarch64
* Appplication : -



----------------------------------------
#### Run

```sh
docker run -i -t --rm \
           forumi0721/ubuntu-base:[ARCH_TAG]
```



----------------------------------------
#### Usage

```dockerfile
FROM forumi0721/ubuntu-base:[ARCH_TAG]

#For cross compile on dockerhub (aarch64)
RUN ["docker-build-start"]

RUN 'build-code'

#For cross compile on dockerhub  (aarch64)
RUN ["docker-build-end"]
```



----------------------------------------
#### Docker Options

| Option             | Description                                      |
|--------------------|--------------------------------------------------|
| -                  | -                                                |


#### Ports

| Port               | Description                                      |
|--------------------|--------------------------------------------------|
| -                  | -                                                |


#### Volumes

| Volume             | Description                                      |
|--------------------|--------------------------------------------------|
| -                  | -                                                |


#### Environment Variables

| ENV                | Description                                      |
|--------------------|--------------------------------------------------|
| -                  | -                                                |

