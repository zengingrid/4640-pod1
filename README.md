# 4640-pod1

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
![image](https://user-images.githubusercontent.com/71790092/197939701-f05872b4-55c8-439d-a994-721900664fd6.png)
