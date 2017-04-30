# ansible-centos


- Requires Ansible 2.2 or newer
- Expects CentOS 7 hosts

The inventory file 'hosts' defines the nodes in which the stacks should be configured.

        [centos]
        centos ansible_host=192.168.122.100

The stack can be deployed using the following command:

        ansible-playbook -i hosts site.yml
