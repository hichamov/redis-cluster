- This playbook setup a redis cluster of 3 nodes and three shards

- Every node contains two instances of redis (a master and slave)

- Before applying the playbook, set your machines ips in 'inventories/hosts' file, then, modify the 'vars/vars.yaml' to set the ports, and ips of machines

- Finally, apply the 'main.yml' playbook
