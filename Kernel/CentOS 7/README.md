## 下载：  
wget --no-check-certificate https://raw.githubusercontent.com/xiyangdiy/Save/master/Kernel/CentOS%207/kernel-3.10.0-229.1.2.el7.x86_64.tar.gz.001  
wget --no-check-certificate https://raw.githubusercontent.com/xiyangdiy/Save/master/Kernel/CentOS%207/kernel-3.10.0-229.1.2.el7.x86_64.tar.gz.002  
cat kernel-3.10.0-229.1.2.el7.x86_64.tar.gz* | tar zx  
rm -f kernel-3.10.0-229.1.2.el7.x86_64.tar.gz*  
## 安装：  
rpm -ivh kernel-3.10.0-229.1.2.el7.x86_64.rpm --force  
