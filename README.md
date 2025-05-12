# 🕺 IKUN OpenStack 安装助手 · Packstack 版（CentOS7）

一个优雅而暴力的 OpenStack Packstack 自动部署工具，集成**基础环境配置**、**控制节点应答文件生成**、**计算节点虚拟化检测**，为 OpenStack 安装保驾护航。  
由一位酷爱蔡徐坤的 IKUN 精心打造 💿

---

## 🧩 支持特性

- 🔧 一键完成 CentOS 7 的基础环境配置（SELinux、firewalld、NetworkManager、yum源、repo）
- 🧠 控制节点支持自动生成并引导配置 `packstack answer.txt` 文件
- 🖥️ 计算节点支持 CPU 虚拟化检测，杜绝无效资源浪费
- 💃 带有蔡徐坤跳舞彩蛋，安装不再枯燥

---

## ⚙️ 环境要求

- 操作系统：CentOS 7
- 至少一台控制节点（含 packstack）
- 一台或多台计算节点（需支持 CPU 虚拟化）
- 推荐内存：
  - 控制节点 ≥ 8G
  - 计算节点 ≥ 4G

---

## 🚀 使用方式

```bash
curl -O http://cdn.xiaohuang.xyz:9999/bash/openstack/openstack/install.sh && chmod +x install_openstack.sh && ./install_openstack.sh
