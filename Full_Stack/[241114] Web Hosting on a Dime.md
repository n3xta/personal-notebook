# 如何用最省钱的方式host静态网页

## 前置概念

> Hosting is rent for our files

一个案例理解Client → server → files：

我们可以通过ip访问局域网中的其他设备，比如

![](https://raw.githubusercontent.com/n3xta/image-hosting/main/img/202411141416259.png)

↑用ip访问了主机host的文件夹，可以查看其中的文件（例如dime.gif）

## Cloudflare

Cloudflare本来是负责cdn
  - store and deliver web content to users based on their location

但我们可以白嫖cloudflare的服务来host一个github repo

![](https://raw.githubusercontent.com/n3xta/image-hosting/main/img/202411141434435.png)

[从这里链接到git](https://dash.cloudflare.com/feaa7b20033590437a7296eb1aa059e3/workers-and-pages/create/pages)

链接个人账号

![](https://raw.githubusercontent.com/n3xta/image-hosting/main/img/202411141435760.png)

### domain

也在cloudflare上买，是最便宜的

如果从别的地方买了，也可以transfer

![](https://raw.githubusercontent.com/n3xta/image-hosting/main/img/202411141437308.png)

我操，

![](https://raw.githubusercontent.com/n3xta/image-hosting/main/img/202411141439117.png)

这下不得不l33t了

![](https://raw.githubusercontent.com/n3xta/image-hosting/main/img/202411141440732.png)

### bucket

储存桶，可以放static assets
（但你其实也可以，把东西都塞到一个github repo里，就像我现在在做的）

![](https://raw.githubusercontent.com/n3xta/image-hosting/main/img/202411141446140.png)

需要设置dns，在public access里

### limits of free(dom)

- max 100 custom domains
- 10g max storage/month
- 10M requests per month
- 1m uploads/modifications per month

## Namecheap

[namecheap domain to cloudflare](https://www.namecheap.com/support/knowledgebase/article.aspx/9837/46/how-to-connect-a-domain-to-a-server-or-hosting/)