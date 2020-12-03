# vue-next-renting

## 简介

`vue-next-renting` 是一个基于 `vite + vue3` 构建的移动端[视频课程项目](#jump)。

我们可以通过下面的 `gif` 图片来对 `vue-next-renting` 有一个更深的了解（[图片未打开？](http://res.lgdsunday.club/renting-overview.gif)）。

<img src="https://github.com/lgd8981289/vue-next-renting/blob/master/renting-overview.gif" alt="renting-overview" />

## 项目将遵循的 git 规范

### 分支

- master：主分支。用于项目阶段部署发布。
- dev：开发分支。始终保持最新完成以及 bug 修复后的代码。
- feature：新功能分支。用于新功能开发，以 dev 为基础创建。
- release：预上线分支。发布提测阶段。

### 提交

- 提交规范：key: value。比如：新增 首页 -> feat: home / 首页
- key 可选：

  ```
  feat：新功能（feature）
  fix：修补bug
  docs：文档（documentation）
  style： 格式（不影响代码运行的变动）
  refactor：重构（即不是新增功能，也不是修改bug的代码变动）
  test：增加测试
  chore：构建过程或辅助工具的变动
  release: 发布
  ```

## 章节规划（持续更新中...）

- 番外（课程之外的一些说明视频，不在预计之内的视频内容）
- 主章（课程主要章节）
  - 第一章：课程简介
    - 1-1：前言
      - 介绍整个课程项目
      - 明确课程中用到的技术
      - 明确学习该项目需要的技术储备
  - 第二章：Vue 3 新特性 与 vite 讲解
    - 2-1：Vue 3 新特性寻览
    - 2-2：什么是 Composition（组合式） API ？
    - 2-3：入口函数 - setup
    - 2-4：新的响应式机制 - Proxy
    - 2-5：使用 ref 创建响应式变量
    - 2-6：响应式基础 API - reactive
    - 2-7：setup 函数中的 生命周期钩子
    - 2-8：setup 函数中的 watch 响应式变更
    - 2-9：setup 函数中的 computed 属性
    - 2-10：setup 函数中的 Provide / Inject
    - 2-11：有意思的瞬间移动 - Teleport
    - 2-12：章节总结
  - 第三章：万事开头难 - 构建项目与首页开发
  - 第四章：高品质交互体验 - 构建进入二楼组件
  - 第五章：让路由跳转不再生硬 - 城市列表与虚拟任务栈
  - 第六章：地图来了 - 高德地图在 vue3 中的实现
  - 第七章：沉浸式体验 - threejs 实现 3D 全景看房
  - 第八章：不会部署不用怕 - 从买服务器到部署上线全流程
  - 第九章：项目总结

所有的课程视频将 **免费** 发布到 **b 站**。

欢迎大家 `star` ，后续该项目的所有代码将会被 `push`到该仓库中，关于课程内容与问题讨论亦会在本仓库中进行。

[点击跳转查看后续计划](https://github.com/lgd8981289/vue-next-renting/blob/master/docs/%E4%BB%A3%E7%A0%81%E6%9B%B4%E6%96%B0%E4%B8%8E%E8%A7%86%E9%A2%91%E5%8F%91%E5%B8%83%E8%AE%A1%E5%88%92.md)

## 涉及到的技术点

包括但不仅限于以下技术：

- vite（构建工具）
- vue-next（vue3）
- vant-ui（UI 库）
- 高德地图 API（地图相关）
- 虚拟任务栈（介绍：https://juejin.cn/post/6844904199528923143）
- threejs（3D 全景）
- animejs（动画实现）
- 复杂的自定义组件
- ...

<h2 id = "jump">什么叫视频课程项目？</h2>
以录制视频的形式，来讲解**整个项目中所涉及到的所有技术点**，以及**项目的实现思路、代码、方案等**。

也可以理解为：**手把手教你完成这个项目的开发**

## 接口文档

[点击跳转接口文档地址](https://github.com/lgd8981289/vue-next-renting/blob/master/docs/%E6%8E%A5%E5%8F%A3%E6%96%87%E6%A1%A3.md)

## 声明

为避免纠纷，项目中所涉及到的所有资源均为网络公开资源，如有侵权请联系作者

lgd_sunday@163.com
