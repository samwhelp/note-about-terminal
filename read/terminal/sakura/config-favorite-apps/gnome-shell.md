---
title: GNOME Shell
nav_order: 1021
has_children: false
parent: 設定 / Favorite Apps
grand_parent: Sakura
---


# GNOME Shell


## 設定指令


### set

執行下面指令

``` sh
gsettings set org.gnome.desktop.default-applications.terminal exec 'sakura'
```


### get

執行下面指令

``` sh
gsettings get org.gnome.desktop.default-applications.terminal exec
```

顯示

```
'sakura'
```


### reset

執行下面指令

``` sh
gsettings reset org.gnome.desktop.default-applications.terminal exec
```
