# DOCKER-H5AI

## RUN with a basic nginx configuration file

```
$ sudo docker run -d \
  -p 80:80 \
  -v /path/to/serve/from:/var/www \
  michaeljefferys/docker-h5ai
```
