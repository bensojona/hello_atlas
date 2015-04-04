# -*- mode: ruby -*-

VAGRANTFILE_API_VERSION = "2"

Vagrant.configure(VAGRANTFILE_API_VERSION) do |config|
  config.vm.box = "trusty64"
  config.vm.box_url = "http://cloud-images.ubuntu.com/vagrant/trusty/current/trusty-server-cloudimg-amd64-vagrant-disk1.box"
  config.vm.network "private_network", ip: "192.168.33.10"
  config.vm.hostname = "dev"

  config.push.define "atlas" do |push|
    push.app = "jb_hashicorp/hello_atlas"
  end
end
