# -*- mode: ruby -*-

VAGRANTFILE_API_VERSION = "2"

Vagrant.configure(VAGRANTFILE_API_VERSION) do |config|
  config.push.define "atlas", strategy: "standalone_app" do |push|
    push.app = "jb_hashicorp/metamon"
  end
end
