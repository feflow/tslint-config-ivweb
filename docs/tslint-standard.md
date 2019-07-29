## 规则定义准则
* 不重复造轮子，基于tslint配置并改进
* 能够帮助发现代码错误的规则，全部开启
* 目的是团队的代码风格统一，而不是限制开发体验

## tslint-config-ivweb 介绍
 tslint-config-ivweb是腾讯NOW直播IVWEB团队的TSLint配置。目前发布初版，目前大约有160条规则，包含可能存在的错误、变量、代码风格、TS相关几个大的规则板块。

仓库地址：https://github.com/Stevenzwzhai/tslint-config-ivweb
欢迎提交issue或者PR一起参与团队规则维护

## 规则说明

 [规则文档](https://github.com/Stevenzwzhai/tslint-config-ivweb/blob/master/docs/rule.md)

## 项目接入使用

基本理念： 项目代码太多，不影响历史代码。只针对有改动的代码（.ts和.tsx后缀）才进行校验。

第一步：添加或者修改tslint.json 配置文件

``` javascript
{
  "extends": ["tslint-config-ivweb"],
  "linterOptions": {
    "exclude": ["**/node_modules/**"]
  },
  "rules": {
  // your own rule
  }
}
```

第二步：增加tslint、typescript和tslint-config-ivweb依赖

此处我们使用husky来管理所有的Hook，同之前的commit message校验。

```
{
  "name": "with-lint-staged",
  "version": "0.0.1",
  "scripts": {
    "precommit": "lint-staged"
  },
  "lint-staged": {
    "*.{ts,tsx}": [
      "git add"
    ]
  },
  "devDependencies": {
    "tslint": "^5.18.0",
    "tslint-config-ivweb": "^1.0.0",
    "typescript": "^3.5.3"
    "husky": "^0.14.3",
    "lint-staged": "^4.2.3"
  }
}
```