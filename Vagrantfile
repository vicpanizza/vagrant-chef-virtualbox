Vagrant.configure(2) do |config|
  	config.vm.box = "ubuntu/trusty64"
	config.vm.network "private_network", ip: "10.2.1.25" 


	config.vm.provision :chef_solo do |chef|
   		chef.run_list = [ "tomcat::directories" ]
  	end
 
end