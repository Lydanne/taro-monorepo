# Taro Monorepo

## 目录框架

- apps/
  - app => vue3 + ts + nutui4 + taro3
- libs/
  - 存放你的项目库
- scripts/
  - 存放项目脚本的

## 提示

- ! 不要乱升级依赖可能会导致 BUG（本人已踩坑）
- ! 不要使用 pnpm，可以使用 yarn（本人已踩坑）
- ! 该项目推荐使用 yarn

## 功能

- monorepo 管理
- 目录的规范
- git 提交规范

## 运行

### 安装依赖

```bash
yarn
```

### 运行 APP

```bash
yarn workspace app run dev:weapp
```

## About

MIT
