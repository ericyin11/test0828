# gitcode

架构：基于[create-vue](https://github.com/vuejs/create-vue)构建（vite+vue3+pinia+scss）
组件库：[Vue DevUI](https://vue-devui.github.io/)


# 开源协议
本项目基于[Apache License 2.0](./LICENSE)


# 规范
- 使用eslint，保存自动格式化
- 页面和组件文件夹命名及引用为大驼峰（Issue，IssueItem），其他文件夹小驼峰（common）
- 代码内变量，方法名为小驼峰（issueNum）
- css 类名为蛇形（submit-btn-color）
- 分支命名（关键字/模块/功能，fix/mr/bigfile-issue-create）

```
关键字包括：feat、 hotfix、refactor等类型
```

- commit 提交规范（feat：完成 issue 创建功能）

```
feat： 新增功能
fix: 修复 bug
docs: 仅仅修改了文档，比如 README, CHANGELOG, CONTRIBUTE等等
style: 仅仅修改了空格、格式缩进、逗号等等，不改变代码逻辑
refactor: 代码重构，没有加新功能或者修复 bug
perf: 优化相关，比如提升性能、体验11111
test: 测试用例，包括单元测试、集成测试等
chore: 改变构建流程、或者增加依赖库、工具等
revert: 回滚到上一个版本
```

## Customize configuration

See [Vite Configuration Reference](https://vitejs.dev/config/).

## Project Setup

```sh
# 安装依赖
npm install
```

### start

```sh
npm run dev # 开发
npm run prod # 生产
```

### build

```sh
npm run build:dev # 开发
npm run build:prod # 生产
```

### Lint with [ESLint](https://eslint.org/)

```sh
npm run lint
```