---
title: '飞行器制导控制方法及其应用'
subtitle: 'Flight Guidance Control Method and Application'
summary: '研究生教材出版中'
authors: 
- Fenfen Xiong, Jianan Wang, Huan Jiang

tags:
- FGC
- Textbook
categories:
- Posts 

date: "2020-09-09T00:00:00Z"
lastmod: "2020-09-10T00:00:00Z"
featured: false
draft: false

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Placement options: 1 = Full column width, 2 = Out-set, 3 = Screen-width
# Focal point options: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight
image:
  placement: 2
  caption: 'Image credit: [**Baidu Image**](https://pan.baidu.com/s/1mwEzyy_RMUgWRvm--m2lyQ)'
  focal_point: ""
  preview_only: false

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects: []
---

## 前言

在过去的二三十年中，我国空天技术实力不断提升，飞行器信息化和智能化程度不断提高，为适应高精度、大机动、强鲁棒等需求，飞行器的制导和控制面临着新的挑战。随着现代控制理论的不断发展、现代科学技术的不断交叉融合以及机载计算机计算能力的显著提升，如何在飞行器制导控制系统设计中应用最优控制、鲁棒控制、变结构控制等先进控制理论以及数值计算和优化算法，在满足各类约束的同时提高制导精度和抗干扰能力，已成为国内外研究的重要课题，近几年涌现出了丰硕的研究成果。

本书以作者的部分研究成果为基础，同时综合参考了大量的国内外文献资料，在对传统的飞行器制导控制理论进行简要描述的基础上，重点介绍了目前在飞行器制导控制中具有较好应用前景的几种现代控制方法，内容上较为新颖前沿。在介绍上紧扣飞行器这一被控对象，方法推导过程追求简明扼要，行文中尽量避免复杂的控制理论与数学运算，重视理论内涵而非数学上的完备性析构证明，使得读者既能方便地理清控制方法的来龙去脉又可较快地将方法应用于工程实践。

本书共包含7章内容。第一章绪论，介绍了飞行器制导控制系统的基本组成与功能。第二章介绍了飞行器制导控制的基本原理与实施控制的一些技术途径。第三章介绍了飞行器制导控制的数学建模方法与分析手段。第四章介绍了几类基于滑模变结构控制的制导律及其在飞行器制导中的应用。第五章介绍了预测-校正、牛顿迭代求根、滚动凸优化几类计算制导方法及其应用。第六章介绍了飞行器鲁棒变增益控制方法及其应用。第七章介绍了多飞行器系统协同制导方法及其应用。 

本书1~4章和6章由熊芬芬编写，第5章由熊芬芬和姜欢共同编写，第7章由王佳楠编写。全书由熊芬芬和姜欢统稿和审核。在本书的编写中我们参考和引用了国内外众多学者的研究成果，在此向这些作者表示衷心感谢。本书初稿曾作为研究生课程讲义的形式使用，历届授课学生提出了许多宝贵意见。在编著教材的过程中得到了课题组林启璋、安泽、吴杰、梁卓楠、李超、冉雨林、李泽贤等研究生的大力支持，他们也参与了部分章节内容的文字录入、编写和全书的整理校核工作。在此一并对他们表示感谢。本书受北京理工大学研究生精品教材项目资助，在此深表感谢。感谢北京理工大学出版社张海丽编辑的大力支持和帮助。

由于编者在时间和经验上的欠缺，书中难免出现错误与不足，敬请广大读者批评指正。
编者
2020年8月26日










