VAGRANTFILE_API_VERSION = "2"

Vagrant.configure(VAGRANTFILE_API_VERSION) do |config|
    config.vm.box = "precise32"
    config.vm.box_url = "http://files.vagrantup.com/precise32.box"

    config.vm.network "private_network", type: "dhcp"

    config.vm.provision "ansible" do |ansible|
        ansible.playbook = "site.yml"
    end
end
