# Linux Ansible Bootstrap

If VirtualBox network is NAT, add a VirtualBox port-forward rule:

| **Field**  | **Value** |
| ---------- | --------- |
| Name       | ssh       |
| Protocol   | TCP       |
| Host Port  | 2222      |
| Guest Port | 22        |

 
Then connect from your host machine:
```
ssh -p 2222 your_linux_username@127.0.0.1
```
