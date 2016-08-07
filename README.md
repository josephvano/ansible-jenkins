# Ansible Jenkins Role

This is an example of installing Jenkins CI software on a CentOS 6.5 machine. It is using Vagrant to provision the machine and ansible to install the necessary software.

There is an additional role of nginx to set it up as a reverse proxy listening on port 80 to the local Jenkins instance.

## Variables

There are some variables that you can change

### nginx

I am using a specific IP within the Vagrantfile that you can change. You must also update the web_hostname variable within the nginx defaults yml file.

* nginx_worker_processes
* web_hostname
* sitename

