## Install Openshift
https://docs.ansible.com/ansible-tower/latest/html/administration/openshift_configuration.html#database-configuration-and-usage

## Download installation package for Openshift
```
wget https://releases.ansible.com/ansible-tower/setup_openshift/ansible-tower-openshift-setup-latest.tar.gz
tar xvzf ansible-tower-openshift-setup-latest.tar.gz
```

 ./setup_openshift.sh -i ~/ansibletower/inventory
export TOWER_HOST=https://ansible-tower-web-svc-secondtower.apps.ocp4.disconnect.blue
export TOWER_USERNAME=admin
export TOWER_PASSWORD=userpass

