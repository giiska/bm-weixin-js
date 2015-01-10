bm-weixin 微信 2015-1-9 新 js sdk 封装
===============

## 微信分享 js 封装

### example
```javascript

  // 分享
  ns.setWeixinShare({
    imgUrl: 'https://avatars3.githubusercontent.com/u/5893693?v=3&s=460',
    link: 'https://github.com/bammoo',
    title: 'bammoo\'s github',
    success: function() {
      // 成功后回调
    }
  })
```

## 微信获取网络状态接口 js 封装

### example
```javascript
  ns.getNetworkType(function(networkType) {
      // networkType 取值为 2g，3g，4g，wifi
      // 成功后回调
  })
```