# Description

### This repo:

* configures yum for docker
* installs docker on Target Node
* start and enable docker service
* install python36 if not available
* install docker pip module for anible
* pulls httpd docker image from docker hub registery
* creates httpd container, recreate if already exist and exposes container (patting/ port forwarding)
* copies a target webpage into running httpd container
