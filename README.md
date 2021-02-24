# 前端框架（node+react)

## 技术栈

- koa
- gulpfile（自动化打包）
- webpack
- react
- typescript
- eslint(代码校验)
- react-router(前端路由)
- redux(状态管理)
- axios(请求库)


## 目录

### bin
基本脚本（启动脚本，打包脚本等）

### src

```
- @common(多项目公共文件)
    - web
        - @helper(公共helper，包含业务逻辑)
        - @utils(公共辅助函数，不包含业务逻辑)
        - @types(公共类型)
    - server
        - @helper(公共helper，包含业务逻辑)
        - @utils(公共辅助函数，不包含业务逻辑)
        - @types(公共类型)
    - build(构建相关)


- sever(服务器)
    - @types(类型)
    - controller

- web(前端页面)
    - @types(类型)
```

#### 