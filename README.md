Open Data Portal
================

Welcome to the Chattanooga Public Library's Open Data Portal initiative! 

## Instructions for Local Development

To replicate the CPL's official development environment you will require a number of open source tools, specifically: 

* [Oracle VirtualBox](https://www.virtualbox.org/)
* [Vagrant](http://www.vagrantup.com/)
* [Ansible](http://www.ansible.com/home)

Furthermore this guide assumes you are developing on a *nix-based machine, as Windows is not fully supported by all the tools used here. With that important caveat noted, please don't let this be a deterent to those pioneers who want to dive in on a Windows machine!

### VirtualBox

VirtualBox is relatively straight forward to install. Please visit the [download page](https://www.virtualbox.org/wiki/Downloads) for installation instructions specific to your operating system.

Ubuntu:
```bash
sudo apt-get install -y virtualbox
```

Fedora:
```bash
sudo yum install -y virtualbox
```

### Vagrant

Please visit the [downloads page](http://www.vagrantup.com/downloads.html) to find an appropriate binary for your operating system.

### Ansible

Please visit the [installation page](http://docs.ansible.com/intro_installation.html#running-from-source) to find the most appropriate route for you to install Ansible. At the time of this writing Ansible 1.5 (most recent version) has not been released to the `yum` repositories so I installed from source. The rationale stemmed from needing a solution introduced in Ansible 1.5 regarding the `git` module.

### Clone the Open Data Portal Repository