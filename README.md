# Ansible --> AWS -->Linux/Nginx/Goapp deployment example

Running the playbook:
#!/bin/bash
# Run with:
# ./ansible -K --limit production provision.yml
/usr/bin/env ansible-playbook -i hosts "$@"

