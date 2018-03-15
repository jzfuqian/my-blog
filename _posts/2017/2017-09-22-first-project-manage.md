---
layout: post
title: "初体验·项目管控心得"
description: "初次项目管控经验分享"
categories: [体会,心得]
tags: [项目管控]
redirect_from:
  - /2017/09/22/
---


依据个人这两个月的项目管控体验，总结了在我们公司项目管控一些相关的要注意的地方。

## 项目设计和安排

项目开始前需要有一份初步的计划。

项目设计中要确定的元素：

1. 需要做啥 —— 找产品经理确认
2. 做成啥样 —— 找产品经理确认
3. 如何去做 —— 根据以上去设计

项目计划中的安排主要是对工时的预估和排布，要明确的元素：

1. 计划总工时 —— 决定上线时间范围
2. 计划详细时间安排 —— 决定参与人员数量和要求的战力

## 项目每日进度管控

在项目的开发阶段，难免会遇到影响进度的问题，需要实时管控。

日常管控过程中涉及：

* 每日进度汇总
	1. 参与项目每个人进度
	2. 汇总项目每个人进度
* 每日异常汇总
	1. 统计项目每个人异常
	2. 汇总项目每个人异常
* 每日变更汇总
	1. 根据项目进度、异常调整项目安排
* 每日文件汇总
	1. 统计项目每个人文件
	2. 汇总项目每个人文件
* 每日代码检查
	1. 每日个人代码检查
	2. 挑选出特例讲解<font color="red">解决方案</font>

管控日志要求：

1. 如实录入 —— 利于统计评估组员综合能力
2. 要做汇总 —— 经常看整体项目进度
3. 异常变更要明确 —— 到人到时

## 测试管理

在项目开发完成后，需要进行简单的一轮测试，而测试过程中的侧重点则需要根据测试用例。

一轮测试重点：

1. 无低级错误 —— 直接报错类型
2. 无业务逻辑错误 —— 影响原有流程
3. 满足最低要求 —— 视不同项目情况而定

测试用例：

1. 测试点 —— 产品方列出
2. 测试方法 —— 产品方给出描述
3. 测试统计 —— 产助统计结果

测试跟进：

1. 带领项目参与人解决测试产生bug，争取一轮测试问题在一天的时差以内解决
2. 项目经理需要汇总安排产生的bug，bug记录每日需要产助统计给项目经理

## 上线管理

参与人的代码提交

1. 列出项目相关的环境（CPS、ASMS、CPSLINK、ES、ESLINK、CDS、图片服务器、文件服务器等）
2. 根据环境列出<font color="red">前台、后台</font>补丁，给出表格
3. 参与人给出自己的定版提交记录或补丁文件，填到对应表格
4. 项目经理汇总
5. 交由产助跟进更新事宜（一般需要协助产助）

上线后的非代码统计跟进

1. 要添加的环境配置清单
2. 要开启的接口权限清单
3. 服务器的内外网确认

以上问题排查最终要以终测环境OK为准，自觉自测。

## 项目验收

正常上线之后，需要对项目进行验收，项目经理需要给出相应的文档

1. 立项表
2. 时间安排表
3. 测试清单
4. 项目奖分配清单

## 产品经理作用

1. 在项目需求不明确时，需要找产品经理确认
2. 在项目逻辑不明朗时，需要找产品经理核实
3. 在项目时间不可控时，需要找产品经理沟通
4. 产品经理需要定期查看项目情况，避免结果与需求不符

## 产品助理作用

1. 协助跟进项目
2. 协助确定需求
3. 协助推进项目

## 技术经理作用

1. 在技术实现有困难时，需要找技术经理商榷
2. 在代码框架不明确时，需要找技术进了确定
3. 各组技术经理要定期查看代码提交情况，避免出现太多不可控代码


