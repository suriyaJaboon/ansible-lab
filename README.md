# **Ansible-Lab-Test**
Lab-test ansible deploy 

## Require
```py
1. Ansible (version >= 2.3.2.0)
2. Server (guide [mv or docker or lxc])
3. CentOS-7
```
### Step 1
`install Operating System CentOS-7`

### Step 2
```py
$ ansible-playbook -i hosts/dev-lab httpd.yml
$ ansible-playbook -i hosts/dev-lab nodejs.yml
$ ansible-playbook -i hosts/dev-lab mongodb.yml
```