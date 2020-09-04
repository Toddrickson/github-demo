# -*- mode: ruby -*-
# vi: set ft=ruby :
Vagrant.configure(2) do |config|
  config.vm.define  "khaleesi", primary: true do |khaleesi|
    khaleesi.vm.hostname = "khaleesi"
    khaleesi.vm.box = "hashicorp/bionic64"
    khaleesi.vm.network :private_network, ip: "192.168.33.11"
    khaleesi.vm.provision :shell, path: "ansible.sh"
  end
  config.vm.define  "drogon2" do |drogon2|
    drogon2.vm.box = "hashicorp/bionic64"
    drogon2.vm.hostname = "drogon2"
    drogon2.vm.network :private_network, ip: "192.168.33.12"
    drogon2.vm.provision :shell, path: "python.sh"
  end
  config.vm.define  "rhaegal3" do |rhaegal3|
    rhaegal3.vm.box = "hashicorp/bionic64"
    rhaegal3.vm.hostname = "rhaegal3"
    rhaegal3.vm.network :private_network, ip: "192.168.33.13"
    rhaegal3.vm.provision :shell, path: "python.sh"
  end
  config.vm.define  "viserion4" do |viserion4|
    viserion4.vm.box = "hashicorp/bionic64"
    viserion4.vm.hostname = "viserion4"
    viserion4.vm.network :private_network, ip: "192.168.33.14"
    viserion4.vm.provision :shell, path: "python.sh"
  end
  config.vm.define  "snipeuno", primary: true do |snipeuno|
    snipeuno.vm.box = "centos/7""
    snipeuno.vm.hostname = "snipeuno"
    snipeuno.vm.network :private_network, ip: "192.168.33.16"
    snipeuno.vm.provision :shell, path: "python.sh"
  end
  config.vm.define  "tigertone" do |tigertone|
    tigertone.vm.box = "centos/7"
    tigertone.vm.hostname = "tigertone""
    tigertone.vm.network :private_network, ip: "192.168.33.15"
    tigertone.vm.provision :shell, path: "python.sh"
  end
  config.vm.define  "solitaire" do |solitaire|
    solitaire.vm.box = "centos/7"
    solitaire.vm.hostname = "solitairee"
    solitaire.vm.network :private_network, ip: "192.168.33.17i"
    solitaire.vm.provision :shell, path: "python.sh"
  end
  config.vm.define  "blackbird" do |blackbird|
    blackbird.vm.box = "centos/7"
    blackbird.vm.hostname = "blackbird"
    blackbird.vm.network :private_network, ip: "192.168.33.16"
    blackbird.vm.provision :shell, path: "python.sh"
  end

  end
  # Enable provisioning with a shell script. Additional provisioners such as
  # Puppet, Chef, Ansible, Salt, and Docker are also available. Please see the
  # documentation for more information about their specific syntax and use.
  # config.vm.provision "shell", inline: <<-SHELL
  #   apt-get update
  #   apt-get install -y apache2
  # SHELL
  end
end
