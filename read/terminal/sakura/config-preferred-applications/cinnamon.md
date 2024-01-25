---
title: Cinnamon
nav_order: 1022
has_children: false
parent: 設定 / Preferred Applications
grand_parent: sakura
---


# Cinnamon


## 設定指令


### set

執行下面指令

``` sh
gsettings set org.cinnamon.desktop.default-applications.terminal exec 'sakura'
```


### get

執行下面指令

``` sh
gsettings get org.cinnamon.desktop.default-applications.terminal exec
```

顯示

```
'sakura'
```


### reset

執行下面指令

``` sh
gsettings reset org.cinnamon.desktop.default-applications.terminal exec
```
