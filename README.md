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
```bash
ansible-playbook configure_podman.yml --private-key id_rsa -u root
```
results
![image](https://user-images.githubusercontent.com/71790092/197962437-e81f6cc1-f705-4abe-b814-ecaaa98066af.png)
![image](https://user-images.githubusercontent.com/71790092/197962532-1414a50b-e681-456d-9af6-4ca524afa1f0.png)
![image](https://user-images.githubusercontent.com/71790092/197962621-81fc4366-57ef-481a-9499-e92d8e9e1ab4.png)
![image](https://user-images.githubusercontent.com/71790092/197962661-17a1b7a2-32ea-4a48-a8f3-49088b8688f9.png)
