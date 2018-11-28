Vagrant.configure("2") do |config|
 
    #Configure webserver 1
    config.vm.hostname = "web01" 
    config.vm.box = "nikcbg/nginx64"
    config.vm.network "forwarded_port", guest: 80, host: 8081, auto_correct: true
    config.vm.network "private_network", ip: "192.168.56.11"

    #Configure webserver 2
    config.vm.hostname = "web02" 
    config.vm.network "forwarded_port", guest: 80, host: 8082, auto_correct: true
    config.vm.box = "nikcbg/nginx64"
    config.vm.network "private_network", ip: "192.168.56.12"
   
    #Configure mysql server
    config.vm.hostname="mysql" 
    config.vm.box = "nikcbg/mysql64"

end
