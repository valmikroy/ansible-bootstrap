# ansible-bootstrap
 Ansible playbooks for bootstrapping


- Lint
```
yamllint boostrap.yaml
ansible-lint --offline  -p bootstrap.yaml
```

- Execute
```
ansible-playbook    bootstrap-ubuntu.yaml --extra-vars "user=$(whoami)"
```

