Vagrant.configure("2") do |config|
  config.vm.provision "shell", inline: "echo Hello"

  config.vm.define "master" do |master|
    master.vm.box = "master"
    master.vm.box_url = "http://puppet-vagrant-boxes.puppetlabs.com/debian-73-i386-virtualbox-puppet.box"
  end

  #config.vm.define "db" do |db|
  #  db.vm.box = "mysql"
  #end
end
