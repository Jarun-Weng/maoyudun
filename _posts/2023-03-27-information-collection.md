---
title: 信息收集
layout: post
background: ./image/1.jpg
subtitle: 外网.
artist: artstation.com/antoinecollignon
---



<br>

信息收集是渗透测试的重中之重.

<br>

知己知彼,百战不殆

<br>

# 信息收集的具体流程

## 1.业务资产

靶标(ip地址)

#### 获取企业信息

知识产权 ,备案信息,证书查询 ===>扩大攻击范围 

员工信息,企业基本信息===>社会工程学

常用网站:

爱企查	https://www.aiqicha.com 

备案信息查询	http://www.beianx.cn/

证书查询	https://crt.sh

<br>

#### 网络空间

端口,中间件,C段,网站所用框架

常用网站:

FOFA 	https://fofa.info

通过语法可进行精准查询 如:ip="39.156.66.1/24" 查询C段

360		https://quake.360.net

<br>

#### 威胁情报

威胁情报包含威胁源、攻击目的、攻击对象、攻击手法、漏洞、攻击特征、防御措施等

===>事前可以起到预警的作用，在威胁发生时可以协助进行检测和响应，在事后可以用于分析和溯源。

微步上传 情报社区		 https://x.threatbook.cn

奇安信威胁情报中心		https://ti.qianxin.com
360威胁情报中心		  https://ti.360.cn/homepage

<br>

#### 枚举解析

子域名===>扩大攻击范围

在线子域名查询			http://tools.bugscaner.com/subdomain/
DNSGrep子域名查询	 https://www.dnsgrep.cn/subdomain
工具强大的子域名收集器	 https://dnsdumpster.com

<br>

##### 指纹识别

包括系统,中间件,web程序,防火墙四个方面

云悉指纹		https://www.yunsee.cn
潮汐指纹		http://finger.tidesec.net