Vagrant.configure("2") do |config|
  
  config.vm.box = "bento/ubuntu-20.04"
  config.vm.network "public_network", :bridge => 'wlan0'
  config.vm.hostname = "ubuntu20"
  config.vm.provider "virtualbox" do |v|
  v.memory = 1024
  v.cpus = 1
  end


end
