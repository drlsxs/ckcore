# ckcore

## 项目描述
cesium 功能库

## 开始时间
2023年7月16日 18点01分

## 相关资源
项目管理工具： [tapd](https://www.tapd.cn/51936380/board/index?board_id=1151936380001000002&board_type=standard&view_type=standard-board&utm_source=gold_browser_extension)

## git仓库地址


## 项目环境
运行环境
+ node  16.15.0
+ pnpm 6.11.0 

开发工具
+ idea 2023.1.4

## 技术栈

| 库名称    | 文档地址 | 描述        |
|--------|------|-----------|
| rollup |  https://www.rollupjs.com/    | 前端工程化打包工具 |



## 代码提交规范

**注意：** 冒号是英文，后面跟一个英文空格

```shell
git commit -m "feat: 新功能提交"
git commit -m "feat(login): 登录页添加logo"
```

提交格式则如下：

> ```
> <type>`(`<scope>`): `<subject>
> ```

```tex
1. type 为必填项，用于指定 commit 的类型。
   build : 更改构建系统和外部依赖项（如将 gulp 改为 webpack，更新某个 npm 包）
   ci : 对 CI 配置文件和脚本的更改
   docs : 仅仅修改文档说明
   feat : 增加一个新特性
   fix : 修复一个 bug
   perf : 更改代码以提高性能
   refactor : 代码重构时使用
   style : 不影响代码含义的改动，例如去掉空格、改变缩进、增删分号
   test : 增加新的测试功能或更改原有的测试模块

2. scope 为非必填项，用于描述改动的范围，可以是文件的名称，最好包含路径。

3. subject 是必填项，这次提交的日志信息，提交日志必须有意义。
```

