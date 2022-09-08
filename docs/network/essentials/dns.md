# Windows Server 2019 DNS 

## Synospis
In this section I elaborate on how to install and configure a DNS system for an enterprise level company using Vagrant and Virtualbox.

## Vagrantfile

```Ruby
# -*- mode: ruby -*-
# vi: set ft=ruby :

Vagrant.configure("2") do |config|
  config.vm.box = "StefanScherer/windows_2019"
end
```

## Installation and Configuration of Windows Server 2019 DNS


```batchfile
vagrant up
```
