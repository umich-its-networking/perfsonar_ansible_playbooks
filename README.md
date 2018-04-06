# perfsonar_ansible_playbooks

1. get this playbook

2. set up group_vars

vi group_vars/testpoint

3. set up host_vars

cp host_vars/host_vars/template host_vars/hostname
vi host_vars/hostname

ansible-playbook --user root --ask-pass site.yml -v --ask-vault-pass
