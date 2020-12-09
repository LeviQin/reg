### reg.js
常用正则验证

### 可验证类型
+ 手机
+ 邮箱
+ 电话
+ 负浮点数
+ 正浮点数
+ 整数
+ 正整数
+ 负整数
+ 中国邮政编码
+ 日期格式
+ 汉字
+ 数字
+ 特殊字符
+ URL
+ 身份证
+ QQ
+ 微信
+ 车牌
+ 更多后续更新...

### 使用
+ 在需要的地方
```js
const reg = new Reg()
```

+ 验证一个手机号码
```js
const mobile = 18475435623
const val = reg.toRegular(mobile, "手机")
console.log(val) // true

const mobile = 9527
const val = reg.toRegular(mobile, "手机")
console.log(val) // false

const mobile = 9527
const val = reg.toRegular(mobile, "姓名")
console.log(val) // Uncaught Error: xxx类型不存在,请输入正确的正则验证类型!
```
