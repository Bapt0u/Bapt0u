# Hello, mate :wave:

```yml
- name: Self-description
  hosts: Bapt0u
  vars:
    nationality: French
    age: 24
  tasks:
    - name: Working on automating stuff and administrating tools
      community.work:
        state: Present
      register: result
      until: result.timeSpendWorking + age == retirement.age
      delay: 1y    
```

<img align="right" alt=":happy noise:" src="vaultboy.png" width='240'>  

## Technologies & Tools

- Ansible/AWX
- Vault by Hashicorp
- Python/Golang
- Windows Server administration
- Debian/Centos administration
- ![badge1](https://img.shields.io/badge/RTFM-In%20progress-blue?style=flat&logo=bookstack)
