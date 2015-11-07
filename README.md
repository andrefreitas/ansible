# Ansible
My ansible project to configure servers.

# Usage
    ansible-playbook -i production site.yml

# Test
Create the vagrant environment with:

    vagrant up

Access with:

    vagrant ssh

Run the playbook again:

    ansible-playbook -i vagrant site.yml
