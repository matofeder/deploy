OS
You need to have python 2.7 installed on your system.

Ansible
Deploy requires Ansible 2.3.0, which can be installed:

into virtualenv
Install Ansible into python virtualenv
The chose system path is for illustrative purpose, feel free to choose yours.

$ mkdir -p ~/bin/deploy
$ virtualenv ~/bin/deploy/deploy7
# Activate the virtualenv
$ source ~/bin/deploy/deploy7/bin/activate
(deploy7)$ pip install ansible==2.3
