# Ansible role grafana-agent

Ansible role to install Grafana Agent.

## Requirements

NONE

## Role Variables

| Variable Name                     | Description                      | Default        |
|-----------------------------------|----------------------------------|----------------|
| grafana_agent_server_http_address | HTTP Address and Port to bind to | 0.0.0.0:9190   |
| grafana_agent_server_grpc_address | GRPC Address and Port to bind to | 127.0.0.1:9191 |

## Dependencies

NONE

## Example Playbook

```yml
---
- name: Playbook to install Grafana Agent
  hosts: grafana
  gather_facts: yes

  roles:
    - ashleykleynhans.grafana-agent
```

## License

GPLv3

## Author Information

Ashley Kleynhans
