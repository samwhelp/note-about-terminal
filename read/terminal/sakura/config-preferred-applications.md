---
title: 設定 / Preferred Applications
nav_order: 1021
has_children: true
parent: sakura
---


# 設定 / Preferred Applications


## 如何設定

| 環境 |
| --- |
| [GNOME Shell](https://samwhelp.github.io/note-about-terminal/read/terminal/sakura/config-preferred-applications/gnome-shell.html) |
| [Cinnamon](https://samwhelp.github.io/note-about-terminal/read/terminal/sakura/config-preferred-applications/cinnamon.html) |
| [Mate](https://samwhelp.github.io/note-about-terminal/read/terminal/sakura/config-preferred-applications/mate.html) |
| [Xfce](https://samwhelp.github.io/note-about-terminal/read/terminal/sakura/config-preferred-applications/xfce.html) |


## 探索

執行

``` sh
gsettings list-recursively | grep terminal | grep exec
```

顯示

```
org.cinnamon.desktop.default-applications.terminal exec 'mate-terminal'
org.cinnamon.desktop.default-applications.terminal exec-arg '--'
org.gnome.desktop.default-applications.terminal exec 'x-terminal-emulator'
org.gnome.desktop.default-applications.terminal exec-arg '-x'
org.mate.applications-terminal exec 'mate-terminal'
org.mate.applications-terminal exec-arg '-x'
```


## 相關討論

* 「[#3](https://www.ubuntu-tw.org/modules/newbb/viewtopic.php?post_id=364274#forumpost364274)」 - 無法打開終端機
