apache.vm.box = "ubuntu/bionic64" 
apache.vm.network "private_network", type: "dhcp" 
vb.memory = "512" 
vb.cpus = 1 
end 
apache.vm.synced_folder "./paginas-web", "/var/www/html" 
sudo apt-get update 
sudo apt-get install -y apache2 
SHELL 
end 
