# 使用手冊
## 前置作業
1. 安裝ansible
```shell
sudo apt update
sudo apt install -y ansible
```
2. 修改 inventorys/hosts 的 ip 設定
3. 若有ssh-key設定，要更改hosts中的ansible_ssh_private_key_file: 和 ansible.cfg的private_key_file
## 執行方式
```shell
ansible-playbook syslog.yml
```
