# Ansible

## Ansible Configurationh Files
- Priority 1:
	- ANSIBLE_CONFIG (environment variable, with a filename target)
- Priority 2:
	- ./ansible.cfg (An ansible.cfg file, in the current directory)
- Priority 3:
	- ~/.ansible.cfg (A hidden file, called .ansible.cfg, in the users home directory)
- Priority 4:
	- /etc/ansible/ansible.cfg (Typically provided, through packaged or system installation of Ansible)