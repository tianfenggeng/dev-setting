## node 项目 工具

### 单元测试工具
注：均可在浏览器环境和服务端环境进行测试，各有侧重


> 前端项目  Jasmine
`npm install -g jasmine`

初始化：
`jasmine init`

搭配依赖包：
```
npm install jasmine --save-dev
npm install jasmine-spec-reporter --save-dev
```


> 后端项目 Mocha

使用Node.js提供的`assert`模块进行断言
`assert`模块非常简单，它断言一个表达式为true。如果断言失败，就抛出Error。

>> 异步测试

通过异步读取指定文件内容获取表达式，实现测试。
依赖包：`mz`

例：`https://www.liaoxuefeng.com/wiki/1022910821149312/1101756368943712`