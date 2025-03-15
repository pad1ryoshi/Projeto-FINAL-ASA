Vagrant.configure("2") do |config|
    config.vm.box = "roboxes/ubuntu2204"
    config.vbguest.auto_update = false
  
    config.vm.provision :ansible do |ansible|
      ansible.playbook = "playbook.yml"
    end
  
    config.vm.define "rodrigopadilha" do |aluno|
      aluno.vm.hostname = "rodrigopadilha"
      aluno.vm.network "private_network", ip: "192.168.57.10"
  
      aluno.vm.provider "virtualbox" do |vb|
        vb.name = "rodrigopadilha"
        vb.memory = 1024
      end
  
    end
  end