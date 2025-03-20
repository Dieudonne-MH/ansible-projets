Sur la machine ansible

sudo apt update
sudo apt install ansible
yum install python-pip
ansible-galaxy install geerlingguy.pip
ansible-galaxy install geerlingguy.docker
ansible-playbook -i hosts.ini install_docker.yml
apt install python3-pip -y
sudo pip3 install ansible-lint
ansible-playbook -i hosts.ini deploy_v1.yml

