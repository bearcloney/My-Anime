# Megumi-bot
# 前言：憨憨机器人，搭建在本地arm64 r2s的openwrt，docker内，谨慎参考
由于只会用openwrt，于是在opt安装docker  用dockers安装centos7部署go-cqhttp
n#odejs一直装不上，索性又在docker里装notejs，docker版来部署cq-picsearcher-bot

&nbsp;

## 文档目录

> 注意
>

> * [固件获取](固件获取.md)
> * [部署教程](部署方式.md)
> * [搜图拓展](搜图拓展.md)
> * [注意事项](注意事项.md)
> * [参考帮助](参考帮助.md)

* 常用操作
> 进入容器
>* GO： `docker exec -it go/ bin/bash`      
>* RSS：`docker exec -it rss/ bin/bash`      
>* PIC：`docker exec -it pic/ bin/bash`      

> 启动      
>* GO： `./go-cqhttp/go-cqhttp faststart`     
>* RSS：`cd cq-picsearcher-bot`  `npm run test`     
>* PIC：`cd ELF_RSS-x.x.x`       `nb run`



![](https://github.com/bearcloney/Megumi-bot/blob/main/another/megumi.png)


## 感谢以下项目或服务

不分先后

* [RSSHub](https://github.com/DIYgod/RSSHub)
* [Nonebot](https://github.com/nonebot/nonebot2)
* [酷Q（R. I. P）](https://cqp.cc/)
* [coolq-http-api](https://github.com/richardchien/coolq-http-api)
* [go-cqhttp](https://github.com/Mrs4s/go-cqhttp)
