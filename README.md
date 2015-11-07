# Ansible
My ansible project to configure servers.

# Usage
    ansible-playbook -i production site.yml

# Test
Create the machine with:

    vagrant up

Access with:

    vagrant ssh

Run the playbook again:

    ansible-playbook -i .vagrant/provisioners/ansible/inventory/vagrant_ansible_inventory --private-key=.vagrant/machines/default/virtualbox/private_key -u vagrant site.yml
