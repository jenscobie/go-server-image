# -*- mode: ruby -*-
# vi: set ft=ruby :

Vagrant.configure("2") do |config|
  config.vm.box = "goserver"
  config.vm.network :private_network, ip: "192.168.0.1"
  config.vm.network :forwarded_port, guest: 8153, host: 8153
end