ansible-ubuntu
=========

Automate install coding tools to new fresh install ubuntu workstation

List of tools
- JDK 8 or 11
- Golang
- Docker
- NodeJS
- Anaconda Python
- Redis
- VS Code
- will be continued

Requirements
------------

install ansible-playbook and the dependencies
```
sudo apt update
sudo apt install software-properties-common
sudo add-apt-repository --yes --update ppa:ansible/ansible
sudo apt install ansible
```

How to Run
--------------

Checkout the repo and adjust values in file `inventory` base on your environment. eg: `home_user` or `home_dir`

Execute ansible-playbook
```
ansible-playbook -i inventory ubuntu.yaml
```

License
-------

BSD