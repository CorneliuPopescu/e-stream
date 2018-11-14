# Event Streaming

Event Streaming deployment

- Apache Kafka

## Ansible

```bash
# Event Streaming
ansible-playbook deploy-e-stream.yml -i _inventories/e-stream.ini -e @_creds/e-stream.yml --vault-password-file ~/secret-e-stream.txt

# Ansible Vault
ansible-vault create _creds/e-stream.yml --vault-password-file ~/secret-e-stream.txt
ansible-vault edit _creds/e-stream.yml --vault-password-file ~/secret-e-stream.txt
```

## References
