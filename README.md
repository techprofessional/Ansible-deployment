# Ansible --> AWS -->Linux/Nginx/Goapp deployment example

#!/bin/bash
# Run with:
# ./ansible -K --limit production provision.yml
/usr/bin/env ansible-playbook -i hosts "$@"
As the file says, you run it with ./ansib

