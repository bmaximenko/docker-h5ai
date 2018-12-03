# DOCKER-H5AI

## RUN with a basic nginx configuration file



```
$ sudo docker run -d \
  -p 80:80 \
  -v $PWD:/var/www \
  -v $PWD/nginx_config_examples/basic_h5ai.nginx.conf:/etc/nginx/sites-enabled/h5.conf \
  michaeljefferys/docker-h5ai
```
