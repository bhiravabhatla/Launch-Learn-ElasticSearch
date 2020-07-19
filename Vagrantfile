# -*- mode: ruby -*-
# vi: set ft=ruby :

Vagrant.configure("2") do |config|
  config.vm.define "esnode1" do |esnode1|
      esnode1.vm.box = "centos/7"
      esnode1.vm.network 'private_network', ip: '192.168.58.60'
      esnode1.vm.provider "virtualbox" do |v|
       v.memory = 4096
       v.cpus = 2
      end
  end
  config.vm.define "esnode2" do |esnode2|
        esnode2.vm.box = "centos/7"
        esnode2.vm.network 'private_network', ip: '192.168.58.61'
        esnode2.vm.provider "virtualbox" do |v|
         v.memory = 1024
         v.cpus = 2
        end
  end
  config.vm.define "esnode3" do |esnode3|
          esnode3.vm.box = "centos/7"
          esnode3.vm.network 'private_network', ip: '192.168.58.62'
          esnode3.vm.provider "virtualbox" do |v|
           v.memory = 1024
           v.cpus = 2
          end
  end
end
