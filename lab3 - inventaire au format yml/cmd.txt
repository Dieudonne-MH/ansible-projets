nano hosts

cat hosts

ansible -i hosts all -m ping

ansible -i hosts all -m copy -a "dest=/home/vagrant/toto.txt content='bonjour eazytraining'"