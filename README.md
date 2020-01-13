# hostup
Init a remote host with prefered tools

Requirements
- root ssh access or sudoer
- ansible

# usage
```bash
# root
$ ansible-playbook -i <host_ip>, user.yml tools.yml --user root
# sudoer
$ ansible-playbook -i <host_ip>, user.yml tools.yml -b --user <user> --ask-pass --ask-become-pass -c paramiko
```

# license
MIT
