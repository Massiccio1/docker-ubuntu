# docker-ubuntu

ubuntu base docker image with:

- python 
- pip 
- nodejs 
- npm
- git
- starship shell
- /shared folder

It features the admin user `test:test` with access to `sudo` commands without password to use scripts and packages that require a non-root user

Run the container with:
```
docker run -it massiccio/my-ubuntu:latest
```
Or with a shared folder:
```
docker run -it -v /path/to/shared:/shared massiccio/my-ubuntu:latest
```