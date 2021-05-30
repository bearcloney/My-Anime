# Megumi-bot
# 前言：憨憨机器人，搭建在本地arm64 r2s的openwrt，docker内，谨慎参考
#由于只会用openwrt，于是在opt安装docker  用dockers安装centos7部署go-cqhttp
n#odejs一直装不上，索性又在docker里装notejs，docker版来部署cq-picsearcher-bot

&nbsp;

## 准备：拉取部署CentOS_7、node.jsPython

1. 使用docker拉取centos7；node.js；python镜像（不用rss可以不下python）
    `Docker pull centos:7

     Docker pull node:latest
 
     Docker pull python:latest`

创建容器centos7&nodejs
docker run --restart always -itd --net host --name go centos:7 /bin/bash
docker run --restart always -itd --net host --name pic node:latest /bin/bash
docker run --restart always -itd --net host --name rss python:latest /bin/bash
#查看容器运行状态
docker ps
访问容器内centos7
docker exec -it go/ bin/bash
docker exec -it pic/ bin/bash
docker exec -it rss/ bin/bash
