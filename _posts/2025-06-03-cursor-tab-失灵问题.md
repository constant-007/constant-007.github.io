---
layout:       post
title:        "cursor tab 失灵问题"
author:       "小星星也变奏"
header-style: text
catalog:      true
tags:
  - cursor
---

## 问题

cursor tab补全经常失效

## 原因

VPN代理不支持http2

## 解决

进入cursor的vscode设置，搜索`http2`，勾选`Disable Http2`，重启cursor即可。
