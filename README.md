# 15March2021 - Docker Set-Up on Ubuntu 18.04 instances


```

Upgrade all libraries
$sudo apt-get update 

Install & Enable Docker
$sudo apt install docker.io -y
$sudo systemctl enable docker

Start Docker in case its not already started
$sudo systemctl start docker
$sudo systemctl status docker

Add ubuntu to docker user group
$sudo usermod -aG docker ubuntu

Log off & Log back in so that the user group permissions take affect
$docker --version

$docker run hello-world


```

### Congratulations!! Your Docker Engine is all Set-up!!
