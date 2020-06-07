---
title: intellijSettings
author: tommy
tags:
  - intellij
categories:
  - tools
toc: true
date: 2018-10-04 09:27:17
---

# 簡介

> Intellij設定


<!--more-->
# 內容




## 消除intellij `import *`

![](intellijSettings/20190303113813.png)



## intellij codeStyle


![codeStyle](intellijSettings/20190303114751.png)

![codeStyle](intellijSettings/20190303115810.png)

![codeStyle](intellijSettings/20190303115631.png)


















## 把Intellij設定檔同步到Github，可以在其他地方匯入

![](intellijSettings/20181004090549.png)

- 看到一個同步的聯結網址
- github創建一個目錄，貼上去
- 要求取得"Personal access tokens"

![](intellijSettings/20181004093455.png)
![](intellijSettings/20181004093549.png)
![](intellijSettings/20181004093632.png)
![](intellijSettings/20181004094350.png)

- https://github.com/yudady/intellijSettings.git
- 開始同步數據，你懂得！ 

![](intellijSettings/20181004094744.png)


# 變更設定目錄
> idea.properties
```java
#---------------------------------------------------------------------
# Uncomment this option if you want to customize path to IDE config folder. Make sure you're using forward slashes.
#---------------------------------------------------------------------
# idea.config.path=${user.home}/.IntelliJIdea/config
idea.config.path=D:/install/JetBrains/ideaIU-2018.2.2/.IntelliJIdea2018.2/config
#---------------------------------------------------------------------
# Uncomment this option if you want to customize path to IDE system folder. Make sure you're using forward slashes.
#---------------------------------------------------------------------
# idea.system.path=${user.home}/.IntelliJIdea/system
idea.system.path=D:/install/JetBrains/ideaIU-2018.2.2/.IntelliJIdea2018.2/system
#---------------------------------------------------------------------

```

# 參考資料


