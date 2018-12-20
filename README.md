# dev_docker
Docker Development/Playground

### Install on OSX
`$brew install docker-compose docker-machine docker`

`$brew cask install docker`

```
$docker version
Client: Docker Engine - Community
 Version:           18.09.0
 API version:       1.39
 Go version:        go1.10.4
 Git commit:        4d60db4
 Built:             Wed Nov  7 00:47:43 2018
 OS/Arch:           darwin/amd64
 Experimental:      false

Server: Docker Engine - Community
 Engine:
  Version:          18.09.0
  API version:      1.39 (minimum version 1.12)
  Go version:       go1.10.4
  Git commit:       4d60db4
  Built:            Wed Nov  7 00:55:00 2018
  OS/Arch:          linux/amd64
  Experimental:     false
  ```
#### Set Environment
`$docker-machine create --driver virtualbox default`

`$eval "$(docker-machine env default)"`

### Fire Up Docker Image
https://hub.docker.com/r/skymindops/zeppelin-dl4j/

`$docker run -it --rm  -p 8181:8080 skymindops/zeppelin-dl4j:latest`
