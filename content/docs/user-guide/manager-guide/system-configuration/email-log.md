+++
title = "邮件日志"
weight = 8
description = "查看系统发送邮件的列表记录及状态"
+++

# 邮件日志

邮件日志是在平台使用已定义模板发送邮件的状态回执。通过此功能，用户可以了解使用服务器发送的邮件状态、邮件数量、失败原因。用户可以选择重发发送失败的邮件。

## 邮件日志列表

列表字段：

- **状态**：邮件发送失败或成功的状态回执
- 接收邮箱：对方接受此邮件的邮箱账号。
- 模板类型：触发此模板发送的触发点类型。
- 失败原因：邮件发送失败的原因回执。
- 重发次数：消息重发的次数。
- 发送时间：消息发送的时间。

## 邮件日志查询

可查询字段：

- 状态：分成功和失败两种状态。
- 接收邮箱：对方接受此邮件的邮箱账号。支持模糊搜索。
- 模板类型：触发此模板发送的触发点类型。支持模糊搜索。
- 失败原因：邮件发送失败的原因回执。支持模糊搜索。

## 重发

- 发送失败的邮件，用户可以点击列表中的![三点](/docs/user-guide/manager-guide/image/more-vert.png)按钮，点击`重发`按钮，重发此邮件。

## 更多操作

- [使用choerodon进行通知配置](../message-config)
- [使用choerodon进行消息发送设置](../message)
- [如何发送系统公告](../system-notice)