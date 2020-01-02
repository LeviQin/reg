## validate.js
常用的正则验证封装

## 介绍
+ 邮箱验证
+ 手机号码验证
+ 电话号码验证
+ URL地址验证
+ 特殊字符验证
+ 密码验证(只可以输入字母数字)
+ 身份证号验证（——15位一代身份证和18位二代身份证都包含在内
+ QQ号码验证
+ 微信号码验证
+ 车牌号码验证
+ 其他功能待更新...

## 使用
+ 任意组件引入(示例:手机号码验证)
```js
import { isMobile } from '@/utils/validate.js'
```

+ 使用手机号码正则验证方法
```js
let num = 18474747474
console.log(isMobile(num)) // true
```

+ 其他方法请去validate.js文件查看