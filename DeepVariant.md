# How to install DeepVariant

Basically, we download the Docker image and follow their instrunction (https://github.com/google/deepvariant/blob/r0.10/docs/deepvariant-quick-start.md) but need to translate the commands to MacOS.


1. Install Homebrew (http://brew.sh) to refresh the list of available packages

Please note taht ```apt``` package manager is for Linux but not Mac. Instead, Homebrew is a good option.
```
Unable to locate an executable at "/Library/Java/JavaVirtualMachines/jdk1.8.0_241.jdk/Contents/Home/bin/apt" (-1)
```


2. Install Docker Desktop and set it up (https://docs.docker.com/docker-for-mac/install/)


3. Pull the DeepVariant Docker image after setting up Docker
```
BIN_VERSION="0.10.0"
sudo docker pull google/deepvariant:"${BIN_VERSION}"
```

