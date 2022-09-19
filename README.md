# jenkins-demo

## Installation
透過Docker進行安裝
```bash
docker run -d -v jenkins_home:/var/jenkins_home -p 8080:8080 -p 50000:50000 --restart=on-failure jenkins/jenkins:lts-jdk11
```

```bash
docker images
docker volume ls
docker container ls
docker logs [containerID]
```
copy the following line
![](https://i.imgur.com/GR8u2C1.png)

open borwser past the above code

http://localhost:8080/
![](https://i.imgur.com/i2ivFWS.png)

安裝結果如下
![](https://i.imgur.com/TnAQMlo.png)
