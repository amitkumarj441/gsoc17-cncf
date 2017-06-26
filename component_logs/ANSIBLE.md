# Run Ansible

Once you have your inventory and vars.yaml, you can run ansible:

    # ANSIBLE_LOG_PATH=/tmp/ansible.log ansible-playbook -vvv -e @/root/vars.yaml -i ansible-inventory playbooks/byo/config.yml 2>&1|tee output
  
Check [logs](https://gist.github.com/amitkumarj441/dec42b8cfb54b32f6fa30c047b194475)

   - 16th June, 2017 : [Ansible log_1](https://gist.github.com/amitkumarj441/3c05d7bbe180710e7c9418da188ec37d), [Ansible log_2](https://gist.github.com/amitkumarj441/f2cb304c3a632492be1aa91360886b73)
   
