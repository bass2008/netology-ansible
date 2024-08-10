
# install ansible

sudo apt-get update
sudo apt-get install ansible

# run

ansible-playbook -i inventory.ini hello-start.yml --become --ask-become-pass

