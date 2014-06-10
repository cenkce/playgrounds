# Playgrounds

A bunch of simple vagrant/ansible based playgrounds, with different environments and services installed.

Mostly those vagrant based VMs are used by myself to test or demonstrate things regarding different technologies and/or daemons.

I am publishing those VMs, as they might be able to help people in need of simple playgrounds containing a certain service. Pull requests with new playgrounds are of course always welcome.

## Usage

In order to make use of any playground you need to have a recent version of [Vagrant](http://www.vagrantup.com/) as well as [Ansible](http://www.ansible.com/home) installed on your system. After having done so, just switch to any of the playground directories and execute the `vagrant up` command. The corresponding VM will automatically be build, provisioned and run. A `vagrant ssh` call allows you to *enter* the VM after it has been created.

Further information regarding each playground can be found in its corresponding README file.

## Further reading

A [blogpost](http://www.westhoffswelt.de/blog/2014/6/10/playgrounds-with-vagrant-and-ansible) regarding this repository, which contains some further information can be found in my [personal blog](http://www.westhoffswelt.de/blog/2014/6/10/playgrounds-with-vagrant-and-ansible)
