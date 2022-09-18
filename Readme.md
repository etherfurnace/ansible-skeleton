# Ansible Skeleton 
Ansible项目骨架

# 项目结构

* filter_plugins: 客户端过滤模块
* group_vars: Inventory 资产组变量
* host_vars:主机变量
* inventory： 资产文件目录
* library: 客户端模块
* playbooks: playbook 入口
* roles: role目录
* stage: 用于存放暂时搁置的资产清单
* ansible.cfg: Ansible配置文件

# Ansible Galaxy

Ansible Galaxy 可以用于快速创建Role以及安装社区开放的Role

## 创建一个Role

```
cd ./roles
ansible-galaxy init sample
```