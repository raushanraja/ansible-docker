# ansible-docker


## Test with vagrant
```bash
vagrant up
```

## Run ansible playbook
```bash
ansible-playbook -i hosts server.yml
```

## Hosts
```
[localhost]
127.0.0.1   ansible_connection=local

[ubuntu]
121.121.121.121
```
