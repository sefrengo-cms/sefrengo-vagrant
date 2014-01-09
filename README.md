Sefrengo Vagrant
================

Vagrant setup for developing Sefrengo

## Instructions

- Install [VirtualBox](https://www.virtualbox.org/wiki/Downloads) and [Vagrant 1.4](http://www.vagrantup.com/downloads.html)
- Clone this repo
- Edit your machines `hosts` file add `192.168.56.101 sefrengo.dev`
- Run `vagrant up & vagrant provision` from the root of the cloned repo. (The installation may take a while.)
- Login to the VM with `vagrant ssh`
- Open a web browser on your machine and go to <http://sefrengo.dev>
- Finished work? Shutdown the VM with `vagrant halt` or destroy it completly `vagrant destroy`

## Credentials

### MySQL

Adminer: <http://192.168.56.101/adminer/>

**Root**
Server: `localhost`
Username: `root`
Password: `123`

**sefrengo_dev**
Server: `localhost`
Username: `sefrengo_dev`
Password: `password_dev`
Database: `sefrengo_dev`

**sefrengo_prod**
Server: `localhost`
Username: `sefrengo_prod`
Password: `password_prod`
Database: `sefrengo_prod`
