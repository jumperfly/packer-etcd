# -*- mode: ruby -*-
# vi: set ft=ruby :

Vagrant.configure("2") do |config|
  config.ssh.insert_key = false
  config.vm.box = "file://output-etcd/package.box"
  config.vm.provision "shell", inline: "etcd --version"
end
