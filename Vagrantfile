# -*- mode: ruby -*-
# vi: set ft=ruby :

Vagrant.configure("2") do |config|
  config.vm.provider "virtualbox" do |vb|
    vb.name = "servidor-ubuntu-00"
    vb.memory = "1024"
    vb.cpus = "1"
  end
  config.vm.box = "base"
  config.vm.box = "ubuntu/focal64"
  config.vm.network "public_network", bridge: "wlp5s0"
end
