# ansible to deploy JBoss

Pre-Req

Use Ansible and RHEL 6.x host
Edit Hosts inventory file
Edit group_vars/jboss-servers file to set JBoss configuration parameters needed

# Run playbook

ansible-playbook -i hosts site.yml

When your playbook runs, your JBoss App Server will be running on ports you gave on provided hosts

