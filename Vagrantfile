# -*- mode: ruby -*-
# vi: set ft=ruby :

Vagrant.configure("2") do |config|

  config.vm.box = "ubuntu/trusty64"

   config.vm.synced_folder "../", "/vagrant_data"


   config.vm.provision "ansible" do |ansible|
     ansible.limit = "all"
     ansible.verbose = "vvv"
     ansible.playbook = "tests/test.yml"
   end
end
