# Ansible
My ansible project to configure servers.

# Usage
    ansible-playbook -i production site.yml

# Boostrap a new server
Add the server to production and run:

    ansible-playbook --limit trinity.andrefreitas.pt -i production -u root site.yml -k

# Test
Create the vagrant environment with:

    vagrant up

Access with:

    vagrant ssh

Run the playbook again:

    ansible-playbook -i vagrant site.yml
