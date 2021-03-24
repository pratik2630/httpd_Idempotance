# httpd_Idempotance
Playbook used to make httpd service idempotance in nature.

 Restarting HTTPD Service is not idempotence in nature and also consume more
resources suggest a way to rectify this challenge in Ansible playbook.

To done this I've used handlers concept in Ansible.
This playbook can be run on localhost without any changes.
To run on different target nodes.
Create inventory file with required target host and change host name in playbook.

To run playbook simple use command

ansible-playbook idem_task.yml
