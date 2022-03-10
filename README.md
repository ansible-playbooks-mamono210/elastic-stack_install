[![CircleCI](https://circleci.com/gh/ansible-playbooks-mamono210/elastic-stack_install/tree/main.svg?style=svg)](https://circleci.com/gh/ansible-playbooks-mamono210/elastic-stack_install/tree/main)

This playbook installs Elastic Stack on CentOS7/CentOS8.

# Install Elastic stack

Change to root and execute commands below.

```
ansible-galaxy install -r roles/requirements.yml
ansible-playbook -i localhost, -c local install.yml
```

# Ansible Variables

### Elasticsearch
[geerlingguy/ansible-role-elasticsearch - GitHub](https://github.com/geerlingguy/ansible-role-elasticsearch)

### Java
[geerlingguy/ansible-role-java - GitHub](https://github.com/geerlingguy/ansible-role-java)

### Kibana
[geerlingguy/ansible-role-kibana - GitHub](https://github.com/geerlingguy/ansible-role-kibana)

### Locale
[robertdebock/ansible-role-locale: Configure locale on your system. - GitHub](https://github.com/robertdebock/ansible-role-locale)

### Logstash
[geerlingguy/ansible-role-logstash - GitHub](https://github.com/geerlingguy/ansible-role-logstash)
