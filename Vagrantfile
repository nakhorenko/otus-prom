#ruby 
# -*- mode: ruby -*- 
# vi: set ft=ruby : vsa
Vagrant.configure(2) do |config| 
   config.vm.box = "ubuntu/bionic64" 
   #config.vm.box_version = "2004" 
   config.vm.provider "virtualbox" do |v| 
 v.memory = 1024 
 v.cpus = 1 
end 
 
 config.vm.define "prom" do |prom| 
 prom.vm.network "private_network", ip: '192.168.50.11',  adapter: 8 
 prom.vm.hostname = "prometheus" 
 end 
end 
