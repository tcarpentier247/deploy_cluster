### opensvc custom deployment 

- quick opensvc cluster deployment
- easy customization with variables

### requirements

- ansible (os native or build ansible docker image)

### deployment steps 

- create or update the inventory file to match your hosts configuration
- put the key ansible is going to use for connection to hosts in ssh.private.key
- custom the playbook or create yours to use the roles you need
- run the playbook
