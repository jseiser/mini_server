# mini_server

```bash
unset ANSIBLE_VAULT_PASSWORD_FILE
ansible-playbook -i servers --vault-password-file ./vault-password server.yml
```

```bash
unset ANSIBLE_VAULT_PASSWORD_FILE
ansible-vault encrypt_string --vault-password-file ./vault-password --name 'VAR_NAME' 'VALUE'
```