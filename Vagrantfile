Vagrant.configure("2") do |config|
  config.vm.provider "virtualbox" do |v|
    v.memory = 1024
  end

  config.vm.define "master" do |subconfig|
    subconfig.vm.box = "ubuntu/jammy64"
    subconfig.vm.hostname = "master"
    subconfig.vm.network :private_network, ip: "192.168.200.100"
    #subconfig.vm.provider "virtualbox" do |vb|
    #   vb.memory = 1024
    #end
  end

  config.vm.define "node1" do |subconfig|
    subconfig.vm.box = "ubuntu/jammy64"
    subconfig.vm.hostname = "node1"
    subconfig.vm.network :private_network, ip: "192.168.200.101"
    #subconfig.vm.provider "virtualbox" do |vb|
    #   vb.memory = 1024
    #end
  end

  config.vm.define "node2" do |subconfig|
    subconfig.vm.box = "ubuntu/jammy64"
    subconfig.vm.hostname = "node2"
    subconfig.vm.network :private_network, ip: "192.168.200.102"
    #subconfig.vm.provider "virtualbox" do |vb|
    #   vb.memory = 1024
    #end
  end

  config.vm.define "node3" do |subconfig|
    subconfig.vm.box = "ubuntu/jammy64"
    subconfig.vm.hostname = "node3"
    subconfig.vm.network :private_network, ip: "192.168.200.103"
    #subconfig.vm.provider "virtualbox" do |vb|
    #   vb.memory = 1024
    #end
  end
end