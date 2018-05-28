Deploy VIM, VUNDLE plugins, custom vimrc on your local

OS
You need to have python 2.7 installed on your system.

Ansible
Deploy requires Ansible 2.3.0, which can be installed:

$ virtualenv /tmp/e_deploy
$ source /tmp/e_deploy/bin/activate
(e_deploy)$ pip install ansible==2.3

Vault
create vault_password_file and insert vault password

Group vars
check and change local group vars

Deploy vim
(e_deploy)$ ansible-playbook -i inv site.yml -D
