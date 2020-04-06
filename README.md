Ansible Role:Red Hat Process Automation Manager on OpenShift with BAM on elastic
=========

This role deploys Red Hat Process Automation Manager (the RHPAM-Authoring environment) on OpenShift and event emiiter emitting metrics to an elastic cluster


Test locally
------------
If you want to test this role locally:

```
ansible-playbook -i tests/inventory role_provision.yml \
        -e OCP_PROJECT=rhpamelastic -e "ansible_python_interpreter=/usr/local/bin/python2"
```


