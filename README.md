RANCHER SERVICE DEPLOY
======================

This roles deploy services in rancher

Example Playbook
----------------

Here is a use case :
```yaml
  - hosts: servers
  - vars:
    - stack_name: "STACK_NAME"
    - service_name: "SERVICE_NAME"
    - image_name: "IMAGE_NAME"
  - roles:
     - ansible-role-rancher-services-deploy
```


License
-------

MIT
