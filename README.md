# configserver
servicio de config server 

![Alt text](https://github.com/51NG-L-R1D-D/eurekaserver/blob/master/src/main/resources/fotocreador/diagrama.jpeg)


[![Watch the video](https://github.com/51NG-L-R1D-D/eurekaserver/blob/master/src/main/resources/fotocreador/foto.jpeg)](https://www.youtube.com/watch?v=-jgGxUVY4DE)


### Docker Build and Docker Run Images
```bash
$ docker build . -t config-server-local
$ docker run -d --name config-server-local -p 7000:7000 config-server-local
```
