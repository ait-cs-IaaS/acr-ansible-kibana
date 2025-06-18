# Ansible Role: kibana

This role installs and configures [kibana](https://www.elastic.co/de/what-is/kibana)

## Defaults

```yaml
kibana_stack_version: 9.0.0

kibana_elasticsearch_host: https://localhost:9200
kibana_elasticsearch_username: kibana_system
kibana_elasticsearch_password: Mozart.R0cks!

kibana_elasticsearch_http_ssl_ca: /path/to/local/ca.crt
```
