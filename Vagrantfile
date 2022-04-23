# -*- mode: ruby -*-
# vi: set ft=ruby :

VAGRANTFILE_API_VERSION = "2"

Vagrant.configure(VAGRANTFILE_API_VERSION) do |config|
  config.vm.box = "mansat123/Fedora-Desktop"
  config.vm.network :private_network, ip: "192.168.56.39"
  config.ssh.insert_key = false
  config.vm.network :public_network, :dev => "virbr0", :mode => "bridge", :type => "bridge"

  config.vm.hostname = "portainer"
  config.vm.provider :libvirt do |v|
    v.memory = 4024
    v.cpus = 6
  end
  
  
  config.vm.synced_folder './', '/vagrant', type: 'nfs', nfs_udp: false, nfs_version: 4
  
  # Enable provisioning with Ansible.
  # config.vm.provision "ansible" do |ansible|
  #   ansible.playbook = "main.yml"
  # end

end
