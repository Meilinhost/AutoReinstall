特性优化
自动获取IP地址、网关、子网掩码

自动判断网络环境，选择国内/外镜像，解决速度慢的问题

懒人一键化，无需复杂的命令

解决萌咖脚本中一些导致安装错误的问题

CentOS 7镜像抛弃LVM，回归ext4，减少不稳定因素

注意事项
CentOS默认密码：Pwd@CentOS

Debian&Ubuntu默认密码：Pwd@Linux

安装后请尽快修改密码，Linux系统建议启用密钥登陆。

OpenVZ / LXC架构系统不适用。


wget --no-check-certificate -O AutoReinstall.sh https://git.io/AutoReinstall.sh && bash AutoReinstall.sh
