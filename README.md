<!--
    需要填充的占位符：
    
    README.md
    
        {name}：文档中文名
        {nameEn}：文档英文名
        {urlEn}：文档原始链接
        {domain}：域名前缀
        {adminName}：负责人名称
        {adminUn}：负责人 Github 用户名
        {adminQq}：负责人 QQ
        {repo}：ApacheCN 的 Github 仓库名称
        {dockerName}：DockerHub 仓库名称
        {pypiName}：PYPI 包名称
        {npmName}：NPM 包名称
    
    CNAME
    
        {domain}：域名前缀

    index.html
    
        {name}：文档中文名
        {color}：显示颜色
        {repo}：ApacheCN 的 Github 仓库名称

    asset/docsify-apachecn-footer.js
    
        {repo}：ApacheCN 的 Github 仓库名称
-->

# {name}

> 原文：[{nameEn}]({urlEn})
> 
> 协议：[CC BY-NC-SA 4.0](http://creativecommons.org/licenses/by-nc-sa/4.0/)
> 
> 阶段：机翻（1）
> 
> 趁着年轻生猛，我要再和生活死磕几年。要么我就毁灭，要么我就铸就辉煌。如果有一天，你发现我在平庸面前低了头，那么请向我开炮。--《在路上》

* [在线阅读](https://{domain}.apachecn.org)
* [在线阅读（Gitee）](https://apachecn.gitee.io/doc-template/)
* [ApacheCN 学习资源](http://docs.apachecn.org/)
* [ApacheCN 翻译校对兼职群 713436582](https://jq.qq.com/?_wv=1027&k=VSNtgpjb)

## 贡献指南

为了不断改进翻译质量，我们特此启动了【翻译、校对、笔记整理活动】，开设了多个校对项目。贡献者校对一章之后可以领取千字2\~4元的奖励。进行中的校对活动请见[活动列表](https://home.apachecn.org/#/docs/activity/docs-activity)。更多详情请联系飞龙（Q562826179，V:wizardforcel）。

## 联系方式

### 负责人

* [{adminName}](https://github.com/{adminUn}): {adminQq}

### 其他

*   在我们的 [apachecn/{repo}](https://github.com/apachecn/{repo}) github 上提 issue.
*   发邮件到 Email: `apachecn@163.com`.
*   在我们的 [组织学习交流群](https://www.apachecn.org/#/docs/join) 中联系群主/管理员即可.

## 下载

### Docker

```
docker pull apachecn0/{dockerName}
docker run -tid -p <port>:80 apachecn0/{dockerName}
# 访问 http://localhost:{port} 查看文档
```

### PYPI

```
pip install {pypiName}
{pypiName} <port>
# 访问 http://localhost:{port} 查看文档
```

### NPM

```
npm install -g {npmName}
{npmName} <port>
# 访问 http://localhost:{port} 查看文档
```

## 其它协议

霞鹜文楷采用 [SIL 开放字体协议 1.1](https://github.com/lxgw/LxgwWenKai/blob/main/SIL_Open_Font_License_1.1.txt)。

## 赞助我们

![](http://data.apachecn.org/img/about/donate.jpg)
