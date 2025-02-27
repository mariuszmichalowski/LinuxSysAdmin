---
title: "Linux系统与网络管理"
author: 黄玮
output: revealjs::revealjs_presentation
---

# 第一章：Linux基础（实验）

---

##  GNU is NOT Unix

# 软件环境

---

* [Virtualbox](https://www.virtualbox.org/)
    * 苹果 M1 用户可以使用任意桌面虚拟化解决方案，例如 [UTM](https://mac.getutm.app/)
* Ubuntu 20.04 Server 64bit
* [阿里云 云起实验室 提供的【零门槛云上实践平台】](https://developer.aliyun.com/adc/) 
    * [备用场景资源一](https://developer.aliyun.com/adc/scenario/exp/a12055b0e9e84e5692b05ae25d377ec0)
    * [备用场景资源二](https://developer.aliyun.com/adc/scenario/exp/410e5b6a852f4b4b88bf74bf4c197a57)


# 实验问题

---

* 调查并记录实验环境的如下信息：
    * 当前 Linux 发行版基本信息
    * 当前 Linux 内核版本信息
* Virtualbox 安装完 Ubuntu 之后新添加的网卡如何实现系统开机自动启用和自动获取 IP？
* 如何使用 `scp` 在「虚拟机和宿主机之间」、「本机和远程 Linux 系统之间」传输文件？
* 如何配置 SSH 免密登录？

# 实验报告要求

---

* 使用 `markdown` 格式纯文本
* 使用 [Github Classroom](https://classroom.github.com/classrooms) 管理作业（课堂当日宣讲为准）
* 每次作业应 `commit` 到独立分支并通过 `Pull Request` 分别提交每一次作业
* 实验报告应图文并茂的记录实验过程，证明自己独立完成的实验作业
* 记录自己独立解决的问题和解决办法，并给出问题解决用到的参考资料出处、链接

---

## 评分标准(1/3) {id="checkpoints-1"}

> 以下规则以单次实验报告满分 10 分为例，其他满分分值需要进行等比例调整。

* 实验报告内容完成度「满分 **7分**」
    * 部分完成：**5分**
    * 基本完成: **6分**
    * 少量瑕疵：**7分**

---

## 评分标准(2/3) {id="checkpoints-2"}

* `markdown` 使用规范 「**1分**」
    * 在 github 上在线渲染结果正确无误 （本条违反，本项直接扣 1 分）
    * 所有配图均已上传到 `github` 且在文档内使用「相对路径」引用（禁止使用图片「外链」）（仅本条违反，扣 0.5 分。同时第三条违反，扣 1 分）
    * 代码块正确使用语法高亮标记 （仅有这一条少量违反，本项可以不扣分。超过 5 处代码引用未高亮标记，扣 0.5 分）

---

## 评分标准(3/3) {id="checkpoints-3"}

* `git` 使用规范 「**0.5分**」
    * 在 `PR` 标题中体现了作业序号，例如 `chap0x01`
    * [推荐的目录结构和分支结构](https://c4pr1c3.github.io/cuc-ns/chap0x01/exp.html)
    * `见名知意` 的文件命名，**好评** 示例如 `logged_in.png`, `install_complete.png` 。**扣分** 示例：`1.png`, `新建文本文件.md` 。
* 实验报告结构规范性程度 「**0.5分**」
    * 在实验报告末总结了遇到的问题与解决方案
    * 参考文献/资料引用标准规范
* 按时提交 「满分 **1分**」
    * 晚提交不超过 1 周 **0.5分**

