---
title: weekly 001
date: 2022-07-18 18:00:00
categories: weekly
tags: weekly
---

## 本期文章

### [关于代码评审(CodeReview)那些不得不说的事儿](https://juejin.cn/post/7100874690884796447)

本文作者在学习了[Google Code Review 指南](https://eng-practices-cn.xindoo.xyz/review/index)的基础上；总结了长期做 CodeReview 的好处：提声代码质量、提前发现问题、经验和知识的传递；CodeReview 的关注点：功能性、复杂性、代码风格、文档&注释、代码亮点；还指出了 CodeReview 应该及时；以及注意的礼节，reviewer 写得好的地方也应该点赞；

本文还指导大家如何才能写出对 CodeReview 友好的代码：提交前先做好自审、写清楚变更描述、单个变更竟可能短；

关于 CodeReview 的误区该文也做了合理的反驳，例如 CodeReview 是纯浪费时间？工期很紧没时间去做 CodeReivew;只有高级工程师才有资格 Reivewe 别人的代码？都有测试流程了，为什么还要做 CodeReview？有了 CodeReview 就不需要测试了？只要我在团队推行了 CodeReview 流程，代码质量就会迅速提高？

### [详解 js 继承的那些事儿](https://blog.csdn.net/qq_34574204/article/details/120716964)

本文作者带你学习 js 的继承，原型，原型链的底层知识和原理；你会了解到以下知识什么是继承；为什么要有继承；继承的相关 6 种实现方式及优缺点。

### [贪吃蛇小游戏开发思路分享](https://juejin.cn/post/7051411538577457183)

如何用数组表示游戏地图，数组的周边嗅探，数组边界检测；还有碰撞检测。看完之后，抖音最火的游戏吃掉那个苹果就可以自己写了。

### [TypeScript 泛型中的 K、T、V 等到底是个啥？](https://juejin.cn/post/7084410879223005215)

当你首次看到 TypeScript 泛型中的 T 会感到陌生么？
那么 T 是什么意思呢？图中的泛型变量 T 表示 Type，实际上 T 可以用任何有效的名称代替。除了 T 之外，常见的泛型变量还有 K、V 和 E 等。

- K 全称 Key 表示对象中键的类型；
- V 全称 Value 表示对象中值的类型；
- E 全称 Element 表示元素类型。

### [45 个 GIT 经典操作场景，专治不会合代码](https://mp.weixin.qq.com/s/2p4m63JdsCjBpVku-WaZyA)

本文作者整理了 45 个日常用 git 合代码的经典操作场景，基本覆盖了工作中的需求。

- 读完本篇文章你会了解到以下知识：
- 提交（Committing） 处理，如：commit message 写错了，删除任意 commit 等等；
- 暂存（Staging）处理，如：我需要把暂存的内容添加到上一次的提交（commit）等等；
- 分支（branches）处理：如：我想提交到一个新分支，但错误提交到了 main 等等;
- 变基（Rebasing）和合并（Merging）处理，如：撤销 rebase/merge，有冲突的情况等待。

### [Vite 3.0 发布，下一代的前端工具链](https://www.oschina.net/news/202953/vite-3-0-released)

Vite 3.0 现已于 2022 年 7 月 15 正式发布；Vite3.0 新特性一览；之后 vite 准备每年会发一个大版本。

### [他来了！性能吊打 Node.js 和 Deno 的新一代 javaScript 运行时！](https://mp.weixin.qq.com/s?__biz=Mzg5NDEyMzA2NQ==&mid=2247488883&idx=1&sn=1ec39e6e52849ea2deb2dbbed26cc2df&chksm=c0253825f752b13303aa204bdfa93eb5979999cf5c61224726673f552ab5406ce9a506a6e7b5#rd)

刚开源不到一个月就获得了 19.5k star！看起来马上就会成为 Node.js 和 Deno 的一大竞争对手了！

和传统的 Node.js 这种传统的 javaScript 运行时不同，Bun.js 直接内置了打包器、转译器、任务运行器和 npm 客户端，这意味着你不再需要 Webpack/Rollup/esbuild/Snowpack/Parcel/Rome/swc/babel 就可以直接运行 TypeScript、JSX！

另外，Bun.js 原生支持了数百个 Node.js 和 Web API，包括约 90% 的 Node-API 函数(fs、path、Buffer 等)。

Bun.js 的目标是可以在浏览器之外的其他地方运行世界上大多数 JavaScript，为你未来的基础架构带来性能和复杂性的增强，并通过更好、更简单的工具提高开发者的生产力！

## 友情链接

- [阿里云 TXD 前端周刊](https://github.com/aliyunfe/weekly)
- [前端精度周刊](https://github.com/ascoders/weekly)
- [o2team/tech-weekly]()
- [tnfe/TNT-Weekly](https://github.com/tnfe/TNT-Weekly/)
