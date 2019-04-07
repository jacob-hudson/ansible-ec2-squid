# ansible-ec2-squid

A very bare-bones playbook that executes a series of roles that
1.  Provisions an EC2 instance
2.  Configures the squid proxy on the said instance

Run from the root of this repo like so:
```
ansible-playbook task/ec2_squid.yml -vvvv -e "@ec2_vars.json"
```
