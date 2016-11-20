# Validator
简单易用的 JS 验证库

> 借鉴于 https://github.com/jaywcjlove/validator.js

## 支持规则
required, mobile, email, tel, url, min, max, min_length, max_length, integer

## 使用例子
```Javascript
import Validator from './validator'

let v = Validator.validate({
    value: 'XXXXXX'
    rules: 'required|min_length(6)|max_length(20)',
    errors: '请输入密码。|密码长度最少6位。|密码长度不能超过20位。',
 })
 
let error = v.error
let faild = v.faild
let passed = v.passed
 
```
