# 不使用Inventory执行模块
```
ansible all -i '10.11.25.48,' -m ping --extra-vars "ansible_user=root ansible_password=xx"
```