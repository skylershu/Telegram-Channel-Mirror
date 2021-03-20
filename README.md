# Telegram-Channel-Mirror

> 利用 CloudFlare Workers 搭建 Telegram 频道镜像站，使得国内可以访问。

## 配置项

主文件 [index.js](./index.js)，有如下需配置项

```
Channel URL: 频道链接
```

## 使用方式

1. 在 [CloudFlare Workers](https://workers.cloudflare.com/) 中创建 Workers

2. 使用快速编辑，将 [index.js](./index.js) 中的代码复制粘贴

3. 将修改第一行的 `const origin` 频道链接修改成自己的频道链接

4. 保存并部署，查看效果

## 开源许可

MIT LICENSE.
