# Vagrantfiles

A collection of Vagrantfiles I use to experiment with new Linux distributions.

## Setting up

```bash
$ git clone https://github.com/AlexandreCarlton/Vagrantfiles.git
$ cp -r Vagrantfiles/.vagrant.d ~/.vagrant.d
$ vagrant plugin install vagrant-cachier vagrant-vbguest
```

## Vagrant plugins

Some plugins that I deem to be applicable in any Vagrant use-case:

 - [vagrant-cachier](https://github.com/fgrehm/vagrant-cachier) - reduces the
   amount of coffee you drink while waiting for boxes to be provisioned by
   sharing a common package cache among similar VM instances.

 - [vagrant-vbguest](https://github.com/dotless-de/vagrant-vbguest) -
   automatically installs the host's VirtualBox Guest Additions on the guest
   system.
