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

Unable to find image 'skymindops/zeppelin-dl4j:latest' locally .  
latest: Pulling from skymindops/zeppelin-dl4j . 
b56ae66c2937: Pull complete . 
fb0a3ca3d558: Pull complete . 
f7683d719f3b: Pull complete . 
43357d2c4f71: Downloading [=============================================>     ]  234.6MB/260.3MB . 
66bf99ace796: Downloading [===============================================>   ]  187.6MB/197.2MB . 
f3523bea13ce: Download complete . 
157565c26cc6: Download complete . 
3af56a15109b: Download complete . 
328432ea93a5: Downloading [=======================>                           ]   43.9MB/94.87MB . 
d28a24d1c7bb: Waiting . 
b3aedd303455: Waiting . 
c290aa05203c: Waiting . 
94311157be69: Waiting . 
a8d12281ad50: Waiting . 
babc0ff23d51: Waiting . 
be2e2bb6c9d9: Waiting . 
d4358edc487b: Waiting . 

