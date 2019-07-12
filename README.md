# Creating Codenvy Account

## Installing `Docker`
1. `wget -qO- https://get.docker.com/ | sh`
	* installs `docker` to the Codenvy environment
* `sudo groupadd docker`
	* create the docker group
* `sudo usermod -aG docker $(whoami)`
	* add user to docker group
* Log out and log back in to ensure that permissions have been modified
* Ensure `docker` has been installed by executing the following command
	* `docker`
* `docker run -it eclipse/che start`
	* start the docker service