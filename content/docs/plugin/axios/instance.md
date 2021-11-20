---
title: "创建实例"
linkTitle: "instance"
draft: false
weight: 7
---

您可以使用自定义配置创建 axios 的新实例。

## axios.create([config])

```js
const instance = axios.create({
  baseURL: "https://some-domain.com/api/",
  timeout: 1000,
  headers: { "X-Custom-Header": "foobar" },
});
```

## 实例方法

下面列出了可用的实例方法。指定的配置将与实例配置合并。

### axios#request(config)

### axios#get(url[, config])

### axios#delete(url[, config])

### axios#head(url[, config])

### axios#options(url[, config])

### axios#post(url[, data[, config]])

### axios#put(url[, data[, config]])

### axios#patch(url[, data[, config]])

### axios#getUri([config])
