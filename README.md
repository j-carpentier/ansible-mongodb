# Ansible MongoDB
Install MongoDB on Centos/Red Hat 7 with ansible and replace Firewalld with Iptables

## Installation
- Clone this repository
`https://github.com/j-carpentier/ansible-mongodb.git`

## Usage

1. Tune your own deployement with variables
*`mongod_port, open mongod port with Iptables`
*`dbpath, data folder for mongoDB server`

2. Launch playbook
*`ansible-playbook -i hosts site.yml`

3. Take a break, a coffee maybe :)
