# Ansible MongoDB
Install MongoDB on Centos/Red Hat 7 with ansible and replace Firewalld with Iptables

## Installation
- Clone this repository
`https://github.com/j-carpentier/ansible-mongodb.git`

## Usage

1. Tune your own deployement with variables
11. `mongod_port, open mongod port with Iptables`
12. `dbpath, data folder for mongoDB server`

2. Launch playbook
21. `ansible-playbook -i hosts site.yml`

3. Take a break, a coffee maybe :)
