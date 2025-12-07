# 《大前端基石》

## 引言

随着 “大前端” 概念的兴起，前端开发的技术边界突破浏览器局限，形成了覆盖多端、整合工程化与全栈能力的技术体系。其出现深刻重塑了前端开发的生态与开发者的职业路径，企业对于前端开发岗位的要求也从 “页面绘制者” 逐渐过渡到 “应用解决方案提供者” ，不再满足于单一的页面效果实现，更要求具备跨端适配、工程化落地、全栈协同、性能优化的综合能力。

然而，在前端技术与生态爆炸式迭代的时代背景下，很多开发者早已陷入了困境。不少人在碎片化的学习模式下陷入 “追工具、赶框架” 的循环，看似掌握了大量技术，实则陷入 “基础不牢、体系缺失” 的被动局面。事实上，大前端生态再庞杂，其核心根基始终未变。正所谓 “阳光下没有新鲜事” ，HTML+CSS 的渲染过程、JavaScript 的运行机制、浏览器的工作原理以及工程化的核心思想，这些 “不变的基石” 才是支撑开发者应对技术迭代、破解复杂问题的关键。

《大前端基石》 源于本人多年在 “大前端之路” 上学习与实践的记录和沉淀，它不是一本传统意义上的教程，而是一份聚焦 “底层逻辑与核心原理” 的学习笔记合集。本作会以 “体系化、底层化、实战化” 为核心，将大前端领域的核心知识按 “核心基石 → 技术跃迁 → 跨领域拓展” 三个阶段进行逻辑拆解，内容上既包含传统的前端开发 “三驾马车”，又囊括框架、NodeJS、工程化等全栈知识体系，并在 Docker、CI/CD 等业务落地支撑能力上进行延伸。

我会将自己踩过的坑、整理的知识点、验证过的实践经验都放在这里，希望能为正在前行的前端开发者提供一份 “可沉淀、可复用” 的学习指南，更希望能助你跳出 “工具依赖”，回归技术本质，真正夯实前端开发的核心能力。愿我们都能在纷繁复杂的技术浪潮中，守住基石，稳步前行，真正成长为 “以不变应万变” 的大前端工程师。

## 作者信息

🧙‍♂️ [Duskstar](https://github.com/duskstar9623)  
✉️ duskstar@foxmail.com   

<a href="https://juejin.cn/user/3963103129121591/posts" target="_blank">![Juejin](https://img.shields.io/badge/%E6%8E%98%E9%87%91-%E6%9A%AE%E6%98%9F-%230D6EFD?style=flat&logo=juejin&logoColor=white&labelColor=%231e80ff&color=%23E8F3FF)</a>&nbsp;
<a href="https://www.xiaohongshu.com/user/profile/5fb9d4d60000000001000061" target="_blank">![Xiaohongshu](https://img.shields.io/badge/%E5%B0%8F%E7%BA%A2%E4%B9%A6-%E6%9A%AE%E6%98%9F%E5%90%9B-%23FFE6EA?style=flat&logo=xiaohongshu&logoColor=%23FF2442&color=%23FF2442)</a>&nbsp;
<a href="https://space.bilibili.com/52609516" target="_blank">![Bilibili](https://img.shields.io/badge/Bilibili-%E6%9A%AE%E6%98%9F%E5%90%9B-%23006F9B?style=flat&logo=bilibili&logoColor=white&labelColor=%23fa7298&color=%23F4F9FA)</a>&nbsp;
<a href="https://www.douyin.com/user/MS4wLjABAAAAeepe5xbvBfl3GsuRHeuoH_47mpv1vj9M4Ud7ns5wyx0" target="_blank">![Douyin](https://img.shields.io/badge/%E6%8A%96%E9%9F%B3-%E6%9A%AE%E6%98%9F%E5%90%9B-%23FE2C55?style=flat&logo=tiktok&logoColor=%23FE2C55&labelColor=%23000000&color=%23FFEDF0)</a>

## 授权说明

本作采用 [CC-BY-NC-SA 4.0 协议](LICENSE) 发布，您可自由使用本作内容，但需遵守以下核心规则：

- 您可以复制、发行、展览、表演本作，或通过信息网络传播、分享本作完整内容/部分片段，但必须保留作者署名信息并标注本作 [GitHub 仓库](https://github.com/duskstar9623/big-frontend-cornerstone) 链接
- 不得将本作内容（含衍生内容）用于任何商业目的
- 仅在遵守与本作相同协议或其兼容协议的前提下，您才能分发本作内容的衍生作品，且不得添加额外限制条款
- 本作作者不对内容的准确性、完整性做任何担保，亦不承担因使用本作内容产生的任何直接或间接损失

## 阶段一：核心基石

**01. HTML**

- [HTML 概述](https://www.yuque.com/duskstar/big-frontend-cornerstone/gcwodb62tgmt6r5q)
- [语义化与 SEO](https://www.yuque.com/duskstar/big-frontend-cornerstone/wbs13xhrr7rsyvt0)
- [基础常用元素](https://www.yuque.com/duskstar/big-frontend-cornerstone/plzk2qqp0359740y)
- [HTML 实体](https://www.yuque.com/duskstar/big-frontend-cornerstone/myraqrux4gv660oz)
- [表格元素](https://www.yuque.com/duskstar/big-frontend-cornerstone/zgy1v7ieoz5ntwm8)
- [表单元素](https://www.yuque.com/duskstar/big-frontend-cornerstone/ylua3158c0gh1w17)
- [iframe 元素](https://www.yuque.com/duskstar/big-frontend-cornerstone/tkkssa4hm7gonge7)
- [在网页中使用 Flash](https://www.yuque.com/duskstar/big-frontend-cornerstone/op65u80bd8fuoene)
- [元素 Attribute](https://www.yuque.com/duskstar/big-frontend-cornerstone/gr1m9guahpfyknmm)
- [HTML 常用概念](https://www.yuque.com/duskstar/big-frontend-cornerstone/arfx6mg7ugp1uu9w)

**02. CSS**

- [CSS 语言简介](https://www.yuque.com/duskstar/big-frontend-cornerstone/tc3p6es31ggd1myu)
- [选择器基础](https://www.yuque.com/duskstar/big-frontend-cornerstone/iw5q11he55cf99zf)
- [常见样式声明](https://www.yuque.com/duskstar/big-frontend-cornerstone/zip9me47thbargtn)
- [层叠与继承](https://www.yuque.com/duskstar/big-frontend-cornerstone/hsyaq3hymdkz974d)
- [CSS 属性值计算过程](https://www.yuque.com/duskstar/big-frontend-cornerstone/zxrgl3trgwo6nw9v)

## 阶段二：技术跃迁

敬请期待... ... ...

## 阶段三：跨领域拓展

敬请期待... ... ...