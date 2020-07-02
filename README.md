#### Ansible/Docker centos image/Nginx sample Html file

##### Requirements:
Host file should be change in your server IP
in playbook change the remote_user to your sudo user
 
For running the playbook:
ansible-playbook -i hosts steel.yml --ask-become-pass

for testing the out output:
curl your_server_ip:80