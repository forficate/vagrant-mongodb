Vagrant::Config.run do |config|
  config.vm.box = "ubuntu-precise-64"

  config.vm.forward_port 27017, 27017 #mongodb

  config.vm.provision :puppet do |puppet|
    puppet.manifests_path = "puppet/manifests"
    puppet.module_path    = "puppet/modules"
    puppet.manifest_file  = "default.pp"
  end

end
