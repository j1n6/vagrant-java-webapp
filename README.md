# Vagrant Configuration for a basic Tomcat Java Web Development

## Prerequisite
Install the following dependencies.

* Oracle VirtualBox:   https://www.virtualbox.org 
* Vagrant: http://vagrantup.com


## Packages

* build-essential
* oracle Java
* maven
* ant
* mysql server and client
* tomcat

## Startup
Navigate to the root of this folder. Run this command to startup the virtual environment

	vagrant up

Vagrant will start initilizating and installing all the tools to this virtual machine.

## Reload Vagrant setting
If you are play with any vagrant configuration, to reload simply enter:

	vagrant reload

Once everything is done. you can ssh into the VM by:

	vagrant ssh

## Shutdown
Navigate to the root of this folder. Run this command to shutdown the VM:

	vagrant destroy
