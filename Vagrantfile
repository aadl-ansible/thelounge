# -*- mode: ruby -*-
# vi: set ft=ruby :
Vagrant.configure("2") do |config|
  config.vm.box = "generic/alpine39"
  config.vm.provision "ansible" do |ansible|
    ansible.playbook = "tests/test.yml"
    ansible.compatibility_mode = "2.0"
  end
end
