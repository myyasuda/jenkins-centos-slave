# jenkins-centos-slave

JenkinsのCentos7のDockerコンテナです。

[centos:centos7]: https://hub.docker.com/r/library/centos/ "centos:centos7"
[Docker-Plugin]: https://wiki.jenkins-ci.org/display/JENKINS/Docker+Plugin "Docker-Plugin"
[dockerhub]: https://hub.docker.com/r/myasuda/jenkins-centos-slave/ "Docker Hub"

[centos:centos7]のコンテナをベースに作成しています。  
Jenkinsの[Docker-Plugin]の利用を想定しています。
[dockerhub]にて公開しています。 

pull command
```
docker pull myasuda/jenkins-centos-slave
```

以下のパッケージをインストールしています。

* openssh-server
* supervisor
* oracle-java: 8u91
* git
* subversion


