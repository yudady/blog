---
title: gradle-build
author: tommy
tags:
  - gradle
categories:
  - tools
toc: true
date: 2019-03-03 12:07:20
---

# 簡介

[Gradle api](https://docs.gradle.org/current/dsl/index.html)


<!--more-->
# 內容

## gradle

![gradle](gradle-build/20190302094135.png)

![gradle](gradle-build/20190302094120.png)


## missing method 

![gradle](gradle-build/20190302150546.png)

![gradle](gradle-build/20190302150741.png)

![gradle](gradle-build/20190302150844.png)

![gradle](gradle-build/20190302151030.png)

## metaClass 動態增加第3方已有的功能

![gradle](gradle-build/20190302151304.png)

![gradle](gradle-build/20190302151613.png)

![gradle](gradle-build/20190302152040.png)


********************************************  
********************************************
********************************************
********************************************
********************************************


![gradle](gradle-build/20190302181100.png)

## gradle 是瞎米，能做瞎米 （編成框架）

![gradle](gradle-build/20190302181339.png)

## gradle 優勢
- 靈活度
- 細粒度
- 擴展性
- 兼容性

## 生命週期
![gradle](gradle-build/20190302183109.png)


*****************************

![gradle](gradle-build/20190303012058.png)

![gradle](gradle-build/20190303013009.png)

![gradle](gradle-build/20190303015550.png)


# Project 
> org.gradle.api.Project




## project file api
![gradle](gradle-build/20190303123943.png)



![gradle](gradle-build/20190303124730.png)

![gradle](gradle-build/20190303124918.png)


## 文件定位

![gradle](gradle-build/20190303125248.png)

> 相對於當前工程

![gradle](gradle-build/20190303125511.png)


## 文件複製

![gradle](gradle-build/20190303125925.png)

![gradle](gradle-build/20190303130011.png)

![gradle](gradle-build/20190303130449.png)

> org.gradle.api.file.CopySpec

## loop 檔案夾 (FileTreeElement)
![gradle](gradle-build/20190303140238.png)


## buildscript {}

![gradle](gradle-build/20190303141657.png)

![gradle](gradle-build/20190303142359.png)


## Project dependencies

![gradle](gradle-build/20190303145138.png)

![gradle](gradle-build/20190303151600.png)

## 使用外部命令

![gradle](gradle-build/20190303155517.png)





# Task 創建

## Task 創建1
![gradle](gradle-build/20190303170146.png)

## Task 創建2

![gradle](gradle-build/20190303170146.png)

## Task 執行時間計算

![gradle](gradle-build/20190303181200.png)

## Task doFirst

![gradle](gradle-build/20190303181459.png)


## Task doLast

![gradle](gradle-build/20190303181607.png)


> 只有寫在doFirst，doLast才能在`執行階段`被調用



## Task 執行順序(依賴)

![gradle](gradle-build/20190303181748.png)


![gradle](gradle-build/20190303184655.png)



![gradle](gradle-build/20190303190135.png)


## Task 輸入輸出

![gradle](gradle-build/20190303192258.png)

![gradle](gradle-build/20190303191053.png)

> TaskInputs TaskOutputs

![gradle](gradle-build/20190303191252.png)

![gradle](gradle-build/20190303191430.png)

![gradle](gradle-build/20190303195313.png)


## 指定運行於某個Task之後

![gradle](gradle-build/20190303195611.png)

![gradle](gradle-build/20190303200216.png)


## 引用gradle腳本

![gradle](gradle-build/20190303200433.png)

![gradle](gradle-build/20190303202404.png)

## 自定義插件

![gradle](gradle-build/20190303220346.png)

![gradle](gradle-build/20190303220418.png)

![gradle](gradle-build/20190303220433.png)

![gradle](gradle-build/20190303220614.png)

> 使用

![gradle](gradle-build/20190303220700.png)

# jenkins

![gradle](gradle-build/20190303222748.png)


# 總結

![gradle](gradle-build/20190303223214.png)

![gradle](gradle-build/20190303223511.png)


![gradle](gradle-build/20190303223808.png)




## root project

```
buildscript {}
allprojects(subprojects) {}
subprojects {}
ext {}

```

## 引用外部檔案
> apply from: file("project.gradle")

## 手動匯入一個子模塊
> project(':common') {}

## gradle.properties
> k v 鍵值對





# 參考資料


