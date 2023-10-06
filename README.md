# ansible-bootstrap
 Ansible playbooks for bootstrapping


- Lint
```
yamllint boostrap.yaml
ansible-lint --offline  -p bootstrap.yaml
```

- Execute
```
ansible-playbook -i <IP address>, -u $(whoami) -kK  bootstrap.yaml
```

- To prepare mac osx 
```
brew tap esolitos/ipa
brew install sshpass
```