# Ansible Jenkins Role

This is an example of installing Jenkins CI software on a CentOS 6.5 machine. It is using Vagrant to provision the machine and ansible to install the necessary software.

There is an additional role of nginx to set it up as a reverse proxy listening on port 80 to the local Jenkins instance.

## Requirements

The local machine must have the following installed

* vagrant
* virtual box (if you follow installing vagrant, it will install the necessary dep)
* ansible 2.0+

## Running

To provision the machine
```
vagrant up
```

To destroy the machine
```
vagrant destory
```

## Variables

There are some variables that you can change

### nginx

I am using a specific IP within the Vagrantfile that you can change. You must also update the web_hostname variable within the nginx defaults yml file.

* nginx_worker_processes
* web_hostname
* sitename

