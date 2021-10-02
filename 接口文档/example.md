# 接口文档

## 倒计时

* 创建新的倒计时

``` js
// 这里写一些注意点

{
  url: 'http://www.pitteeful.com/api/v1/createClock',
  method: 'post',
  param: {
    user_id, // int required 还有什么限制往后加
    set_time, // int required
    title, // string required
    desc // string
  },
  returns: {
    code: 201,
    msg: 'success'
  }
}
```
