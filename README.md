# Description

### This repo:

* __configures yum for docker
* installs docker on Target Node
* start and enable docker service
* install python36 if not available
* install docker pip module for anible
* pulls httpd docker image from docker hub registery
* creates httpd container, recreate if already exist and exposes container (patting/ port forwarding)
* copies a target webpage into running httpd container__

In place of __hostname__ put your target node groups ip/hostname

### Areas of Failure

Most problems arises due to improper invertory check your inventory and target nodes.
This repo might only work on __rhel/centos 8__. 
Check this [repo](https://github.com/mykg/docker-installation-ansible) for rhel/centos 7 
