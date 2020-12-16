# Description

### This repo:

* __configures yum for docker__
* __installs docker on Target Node__
* __start and enable docker service__
* __install python36 if not available__
* __install docker pip module for anible__
* __pulls httpd docker image from docker hub registery__
* __creates httpd container, recreate if already exist and exposes container (patting/ port forwarding)__
* __copies a target webpage into running httpd container__

In place of __hostname__ put your target node groups ip/hostname

### Areas of Failure

Most problems arises due to improper invertory check your inventory and target nodes.
This repo might only work on __rhel/centos 8__. 
Check this [repo](https://github.com/mykg/docker-installtion-ansible) for rhel/centos 7 
