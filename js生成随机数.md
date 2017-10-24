##1.随机生成n-m范围内的整数（不包含n和m）
```
Math.round(Math.random()*(m-n)+n+1)
// 生成随机6位数字字符串验证码，范围是111111-999999，不包含首尾
const randCode = Math.round(Math.random()*888886+111111+1) + '';
```
