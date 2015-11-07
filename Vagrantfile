VAGRANTFILE_API_VERSION = "2"

Vagrant.configure(VAGRANTFILE_API_VERSION) do |config|
    config.vm.box = "ubuntu/trusty64"

    config.vm.define "default" do |default|
      default.vm.network "private_network", ip: "192.168.111.222"
    end

    config.vm.provision "ansible" do |ansible|
        ansible.playbook = "site.yml"
        ansible.inventory_path = "vagrant"
    end
end
