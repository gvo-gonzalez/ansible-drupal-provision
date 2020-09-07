REQUIREMENTS

- vagrant installed
- virtualbox installed
- ansible installed

This setup includes ssh keys to be used by ansible and configred in ansible.cfg file so you simply could run

- ansible all -m ping

To test the connection between your host  and the vm

To get it running run the following commands

vagrant up
ansible all -m ping
ansible-playbook stack-provision/playbook.yml

Once completed applying the recipe you can browse http://127.0.0.1:8080 and login as admin/admin to start working with drupal locally
