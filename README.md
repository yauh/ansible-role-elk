# yauh.elk
Ansible (meta) role for setting up Elasticsearch, Logstash, and Kibana

## Requirements
SSH access to the remote machine Java

## Role Variables

```
...
```

## Dependencies
- yauh.elasticsearch
- yauh.logstash
- yauh.kibana

## Example Playbook
Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

```
- hosts: all
  roles:
     - { role: yauh.elk }
```

## License
BSD

## Author Information
Stephan Hochhaus stephan@yauh.de

[https://github.com/yauh](https://github.com/yauh)
