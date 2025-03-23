ansible -i hosts.ini all -m ping
ansible -i hosts.ini prod -m ping
ansible -i hosts.ini client -m ping
ansible -i hosts.ini all -m copy -a "dest=/home/vagrant/toto.txt content='bonjour eazytraining {{ env }}'"