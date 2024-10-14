Vagrant.configure("2") do |config|
  config.vm.define "master" do |subconfig|
    subconfig.vm.box = "ubuntu/jammy64"
    subconfig.vm.hostname = "master"
    subconfig.vm.network :private_network, ip: "192.168.200.100"
  end

  config.vm.define "node1" do |subconfig|
    subconfig.vm.box = "ubuntu/jammy64"
    subconfig.vm.hostname = "node1"
    subconfig.vm.network :private_network, ip: "192.168.200.101"
  end

  config.vm.define "node2" do |subconfig|
    subconfig.vm.box = "ubuntu/jammy64"
    subconfig.vm.hostname = "node2"
    subconfig.vm.network :private_network, ip: "192.168.200.102"
  end

  config.vm.define "node3" do |subconfig|
    subconfig.vm.box = "ubuntu/jammy64"
    subconfig.vm.hostname = "node3"
    subconfig.vm.network :private_network, ip: "192.168.200.103"
  end
end