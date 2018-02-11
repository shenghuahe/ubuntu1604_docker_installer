# ubuntu1604_docker_installer
Install Docker on Ubuntu16.04

### How to run
```
make build
```

### Check Docker is running
```
sudo systemctl status docker
```

### Run the following to run docker commands without `sudo`
```
sudo usermod -aG docker ${USER}
```
This adds your current user to the docker group


#### Thank you for the instructions from https://www.digitalocean.com/community/tutorials/how-to-install-and-use-docker-on-ubuntu-16-04
