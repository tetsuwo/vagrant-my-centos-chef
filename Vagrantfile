# -*- mode: ruby -*-
# vi: set ft=ruby :

# Vagrantfile API/syntax version. Don't touch unless you know what you're doing!
VAGRANTFILE_API_VERSION = "2"

Vagrant.require_plugin 'vagrant-omnibus'
Vagrant.require_plugin 'vagrant-berkshelf'

Vagrant.configure(VAGRANTFILE_API_VERSION) do |config|
  config.vm.box = "nrel/CentOS-6.5-x86_64"
  config.vm.network "private_network", ip: "192.168.33.10"
end
