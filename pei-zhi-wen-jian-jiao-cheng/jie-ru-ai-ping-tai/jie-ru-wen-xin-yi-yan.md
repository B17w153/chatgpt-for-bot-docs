# 🤣 接入 文心一言

文心一言的设置开始于一行 `[yiyan]` ，随后每个账号的设置开始于一行 `[[yiyan.accounts]]`。

## 网页版 Cookie 登录

截止至当前最新的版本， 仅支持通过 Cookie 的方式使用网页版文心一言。

> 请注意：该方法有封号风险（但是过一段时间就会解封），具体原因未知，请自行取舍。

```toml
[[yiyan.accounts]]
BDUSS='xxxxxx'
BAIDUID='xxxxxx'
```

Cookie 获取方法：[Wiki](https://github.com/lss233/chatgpt-mirai-qq-bot/wiki/%E6%96%87%E5%BF%83%E4%B8%80%E8%A8%80-Cookie-%E8%8E%B7%E5%8F%96%E6%95%99%E7%A8%8B)

## 相关设置

**1.使用代理**

这项设置是每个账号独立的。

参考： [#4.-shi-yong-dai-li](jie-ru-openai-de-chatgpt.md#4.-shi-yong-dai-li "mention")
