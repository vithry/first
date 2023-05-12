
Vagrant.configure("2") do |config|

 config.vm.define "test1" do |test1|
  test1.vm.box = "ubuntu/focal64"
  test1.vm.hostname = "test1"

  test1.vm.network :private_network, ip: "192.168.56.101"

  test1.vm.provider "virtualbox" do |v|
    v.name = "test1"
    v.memory = 1024
    v.cpus = 2
  end
 end  

 config.vm.define "test2" do |test2|
  test2.vm.box = "ubuntu/focal64"
  test2.vm.hostname = "test2"

  test2.vm.network :private_network, ip: "192.168.56.102"

  test2.vm.provider "virtualbox" do |v|
    v.name = "test2"
    v.memory = 1024
    v.cpus = 2
  end
 end

end
