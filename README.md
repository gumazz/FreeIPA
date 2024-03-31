This is homework for FreeIPA/LDAP lesson on Otus platform.
Here are the files:
ansible.cfg - Ansible configuration file
README.md - this readme file
Vagrantfile - Vagrant configuration file for VMs provisioning
ansible/hosts - Ansible inventory file
ansible/hosts.j2 - etc/hosts template file
ansible/provision_client.yml - Ansible playbook for configuration of Clients
ansible/provision_server.yml - Ansible playbook for installation of FreeIPA server. Initialization to be executed after that: ipa-server-install

