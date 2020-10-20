# ansible create user
Ansible playbook for creating linux user

#### Usage
Replace `user_name` and `password_hash` according your needs and launch your playbook.

#### Create password hash
You can use `mkpasswd` tool for creating hashed passwords:

```
mkpasswd -m sha-512
```

