# Ansible
My Ansible project to configure servers.

# Usage
    ansible-playbook site.yml

# Boostrap a new server
Add the server to production and run:

    ansible-playbook --limit trinity.andrefreitas.pt -u root site.yml -k
