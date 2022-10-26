# 4640-pod1

for vms in digital ocean:
- ubuntu
- fedora
tag for both: Web

in this repo:
- ansible.cfg
- inventory/inventory file(s)
- README.md
- .gitignore
- user_setup.yml
- configure_podman.yml

once everything is set up: run 
```bash
ansible -m ping -u root all --private-key id_rsa
```
![image](https://user-images.githubusercontent.com/71790092/197946595-83310fbf-9672-4519-9fdd-fdfb3140d1f5.png)

to run tasks:
```bash
ansible-playbook user_setup.yml --private-key id_rsa -u root
```
