---
title: "API"
draft: false
weight: 6
---

## 请求方法

### axios(config)

可以通过将相关配置传递给 `axios` 来请求。

```js
// Send a POST request
axios({
  method: "post",
  url: "/user/12345",
  data: {
    firstName: "Fred",
    lastName: "Flintstone",
  },
});
```

```js
// GET request for remote image in node.js
axios({
  method: "get",
  url: "http://bit.ly/2mTM3nY",
  responseType: "stream",
}).then(function (response) {
  response.data.pipe(fs.createWriteStream("ada_lovelace.jpg"));
});
```

### axios(url[, config])

```js
// Send a GET request (default method)
axios("/user/12345");
```

### 请求方法别名

为方便起见，为所有受支持的请求方法提供了别名。

#### axios.request(config)

#### axios.get(url[, config])

#### axios.delete(url[, config])

#### axios.head(url[, config])

#### axios.options(url[, config])

#### axios.post(url[, data[, config]])

#### axios.put(url[, data[, config]])

#### axios.patch(url[, data[, config]])

##### 注意

当使用别名方法时 `url`， `method` 和 `data` 属性不需要在配置中指定。

## 并发性 (弃用)

请使用`Promise.all`以替换下面的函数。
处理并发请求的助手函数。

```js
axios.all(iterable);
axios.spread(callback);
```
