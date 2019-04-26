
Vagrant.configure("2") do |config|
  config.vm.box = "ubuntu/trusty64"

  config.vm.provider "virtualbox" do |v|
	  v.memory = 2048
  end

  config.vm.define "jenkins" do |m|
    m.vm.network "private_network", ip: "172.17.177.50"
  end
end
