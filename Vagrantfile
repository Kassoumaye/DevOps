

Vagrant.configure("2") do |config|

  # Configuration de la machine virtuelle pour le serveur GitLab
  config.vm.define "gitlab" do |gitlab|
    gitlab.vm.box = "ubuntu/bionic64"
    gitlab.vm.network "private_network", ip: "192.168.33.10"
    gitlab.vm.hostname = "gitlab"
    gitlab.vm.provider "virtualbox" do |vb|
      vb.memory = "2048"
      vb.cpus = 2
    end
  end

  # Configuration de la machine virtuelle pour le serveur Jenkins
  config.vm.define "jenkins" do |jenkins|
    jenkins.vm.box = "ubuntu/bionic64"
    jenkins.vm.network "private_network", ip: "192.168.33.11"
    jenkins.vm.hostname = "jenkins"
    jenkins.vm.provider "virtualbox" do |vb|
      vb.memory = "2048"
      vb.cpus = 2
    end
  end

  # Configuration de la machine virtuelle pour le serveur Ansible
  config.vm.define "ansible" do |ansible|
    ansible.vm.box = "ubuntu/bionic64"
    ansible.vm.network "private_network", ip: "192.168.33.12"
    ansible.vm.hostname = "ansible"
    ansible.vm.provider "virtualbox" do |vb|
      vb.memory = "2048"
      vb.cpus = 2
    end
  end

  # Configuration de la machine virtuelle pour le serveur Elasticsearch
  config.vm.define "elasticsearch" do |elasticsearch|
    elasticsearch.vm.box = "ubuntu/bionic64"
    elasticsearch.vm.network "private_network", ip: "192.168.33.13"
    elasticsearch.vm.hostname = "elasticsearch"
    elasticsearch.vm.provider "virtualbox" do |vb|
      vb.memory = "2048"
      vb.cpus = 2
    end
  end

end
