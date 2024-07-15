# 前言

不知道为啥 现在国内无法访问 docker.com 以及 docker.io,现在 docker 的全部服务都无法访问,下面是关于如何通过 aliyun 去安装 docker 服务.....

```shell
sudo apt-get update
sudo apt-get install     apt-transport-https     ca-certificates     curl     software-properties-common
sudo add-apt-repository "deb [arch=amd64] https://mirrors.aliyun.com/docker-ce/linux/ubuntu $(lsb_release -cs) stable"
# curl -fsSL https://download.docker.com/linux/ubuntu/gpg | gpg --dearmor -o /usr/share/keyrings/docker-archive-keyring.gpg
sudo apt-get install docker-ce docker-ce-cli containerd.io
```
