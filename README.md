# open-api-typescript-request-generator

基于 openapi 规范，生成接口的 request、response 类型声明和请求方法体

## 安装

`npm install open-api-typescript-request-generator`

## 初始化生成配置文件

`apits-gener init`


## 生成接口

`apits-gener gen`

## 只生成指定 name 的配置

```bash
apits-gener gen --name=test
# or
apits-gener gen -n test
```

# tips
1. 如果有代码格式要求，应该在配置中忽略/api中生成的代码