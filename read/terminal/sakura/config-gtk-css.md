---
title: 設定 / gtk.css
nav_order: 1022
has_children: false
parent: Sakura
---


# 設定 / gtk.css


## 設定檔案

* ~/.config/gtk-3.0/gtk.css


## 如何設定

### 設定 Padding

``` css
VteTerminal,
TerminalScreen,
vte-terminal {
    padding: 10px;
    -VteTerminal-inner-border: 0 0 0 4px;
}
```

> 這個設定方式，適用使用「libvte」的「Terminal」。
