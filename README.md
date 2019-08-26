# ansible-milkyway
This repository will host all Ansible projects that I will be working on
and in particular the Ansible Advanced course projects on Udemy.

Roles
-----
- Webserver and MySQL database server deployment with minimal Flask configuration
  - `playbooks/deploy_web_apps.yml`
  - Execution:
    - `ansible-playbook -i inventory/ playbooks/deploy_web_apps.yml -kK --ask-v -t "configure_flask" -l "db_and_web_servers" -vv`


Vault
-----
- Vault key: `ansible`
