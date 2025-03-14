# 面试派

网址 https://www.mianshipai.com/

[双越老师](https://juejin.cn/user/1714893868765373)联合多位精英博主制作，系统专业的前端面试导航，大厂面试规范，开源免费。

## 本地运行

git clone 源代码

```
npm i
npm run docs:dev
```

## 贡献代码

### 要求

- 有自己的博客或开源项目，有一定的关注度和访问量
- 联系作者（vx `fe-wfp`，备注：`面试派贡献者`）

### 方法

- 基于当前 `main` 分支最新代码开发
- 提交 PR 到 `main` 分支
  - 注意查看 commits 和 files changed ，不要有无关记录和改动，否则不予合并
  - 添加 reviewer `wangfupeng1988`
- 管理员每天审核 PR 合并或者回复建议

### 步骤

现在有多人一起维护，为了方便大家高效协作，避免内容冲突，因此设定此步骤。

**1. 制定计划，包括范围和有效期**

范围，即我接下来要完成哪几个题目，每次最多写 5 个。可以是现有的未解答、过期的题目，也可以自己新加的题目，不要重复即可。

有效期，即我要在未来几天之内完成，最长写 5 天。即 5 天之内必须完成，否则过期。

举个例子，今天是 02.07，我计划未来 5 天之内完成 `cross-test.md` 里的这 3 个题目，我需要改动 `cross-test.md` 文件，如下

```md
## 什么是 OOP ，面向对象三要素是什么？

@双越 将于 2025.02.12 之前提交答案。

## 前端常见的设计模式有哪些？以及应用场景

@双越 将于 2025.02.12 之前提交答案。

## 观察者模式和发布订阅模式的区别

@双越 将于 2025.02.12 之前提交答案。
```

这样就代表了我要在 5 天之内解答这 3 个题目。

**2. 把刚才修改的内容提交 PR 到 `main` 分支。**

**3. 接下来几天按计划完成内容，并提交 PR 到 `main` 分支。如过期可能会被其他同学领取。**

## 发布上线

管理员会统一提交 PR ，把 `main` 合并到 `prod-deploy` 分支，合并后即可触发 [actions](https://github.com/mianshipai/mianshipai-web/actions) 并发布上线。
