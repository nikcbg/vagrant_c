Vagrant.configure("2") do |config|
 
    config.vm.hostname="web01" do |node|
      node.vm.box = "nikcbg/nginx64"
      node.vm.network "forwarded_port", guest: 80, host: 8081, auto_correct: true
      node.vm.network "private_network", ip: "192.168.56.11"
 end
  
    config.vm.hostname="web02" do |node|
      node.vm.network "forwarded_port", guest: 80, host: 8082, auto_correct: true
      node.vm.box = "nikcbg/nginx64"
      node.vm.network "private_network", ip: "192.168.56.12"
   end

   config.vm.hostname="mysql" do |node|
     node.vm.box = "nikcbg/mysql64"
  end
end
