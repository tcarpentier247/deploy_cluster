Opensvc custom deployment 
=============================

- quick opensvc cluster deployment
- easy customization with variables

Requirements
------------

- ansible (os native or build ansible docker image)

Deployment steps 
----------------

- create or update the inventory file to match your hosts configuration
- choose or create a user who is allowed to connect through ssh to your hosts
- put his private key in a ssh.private.key file at the root of this project
- custom the playbook or create yours to use the roles you need
- run the playbook

