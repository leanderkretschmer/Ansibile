[minecraft_server]
[Hostname] ansible_user=[User] ansible_become=true 

#*For automatic SSH verifikation*

[minecraft_server]
[Hostname] ansible_user=[User] ansible_ssh_private_key_file=~/.ssh/id_rsa

[hypervisor]
[Hostname] ansible_user=[User]