# -*- mode: ruby -*-
# vi: set ft=ruby :
Vagrant.configure(2) do |config|
  config.vm.define  "khaleesi", primary: true do |khaleesi|
    khaleesi.vm.hostname = "khaleesi"
    khaleesi.vm.box = "bento/ubuntu-16.04"
    khaleesi.vm.network :private_network, ip: "192.168.33.11"
  end
  config.vm.define  "drogon2" do |drogon2|
    drogon2.vm.box = "bento/ubuntu-16.04"
    drogon2.vm.hostname = "drogon2"
    drogon2.vm.network :private_network, ip: "192.168.33.12"
  end
  config.vm.define  "rhaegal3" do |rhaegal3|
    rhaegal3.vm.box = "bento/ubuntu-16.04"
    rhaegal3.vm.hostname = "rhaegal3"
    rhaegal3.vm.network :private_network, ip: "192.168.33.13"
  end
  config.vm.define  "viserion4" do |viserion4|
    viserion4.vm.box = "bento/ubuntu-16.04"
    viserion4.vm.hostname = "viserion4"
    viserion4.vm.network :private_network, ip: "192.168.33.14"

  # Enable provisioning with a shell script. Additional provisioners such as
  # Puppet, Chef, Ansible, Salt, and Docker are also available. Please see the
  # documentation for more information about their specific syntax and use.
  # config.vm.provision "shell", inline: <<-SHELL
  #   apt-get update
  #   apt-get install -y apache2
  # SHELL
  end
end
