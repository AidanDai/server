# Docker Build

## 1 Install Docker

### 1.1 Install Docker for window 10

1. [https://www.microsoft.com/en-us/software-download/windows10](https://www.microsoft.com/en-us/software-download/windows10)

2. [https://docs.microsoft.com/en-us/windows/wsl/install-win10](https://docs.microsoft.com/en-us/windows/wsl/install-win10)

3. [https://blogs.msdn.microsoft.com/commandline/2017/12/08/cross-post-wsl-interoperability-with-docker/](https://blogs.msdn.microsoft.com/commandline/2017/12/08/cross-post-wsl-interoperability-with-docker/)

### 1.2 Install Docker for others

[https://docs.docker.com/install/](https://docs.docker.com/install/)

## 2 Docker Build in local

```bash
sudo docker build . -t webaidan/server:lts -f docker/Dockerfile

sudo docker build . -t webaidan/$appNameEnv:lasted -f docker/Dockerfile.env

sudo docker build . -t webaidan/$appName:lasted -f docker/Dockerfile.app
```


