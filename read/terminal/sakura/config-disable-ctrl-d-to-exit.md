---
title: 設定 / Disable `ctrl + d` to exit
nav_order: 1023
has_children: false
parent: sakura
---


# 設定 / Disable `ctrl + d` to exit


## Link

* Search: [bash ctrl d](https://www.google.com/search?q=bash+ctrl+d)
* Bash Reference Manual / 8.4.3 Commands For Changing Text / [end-of-file (usually C-d)](https://www.gnu.org/software/bash/manual/bash.html#index-end_002dof_002dfile-_0028usually-C_002dd_0029)
* Bash Reference Manual / 5.2 Bash Variables / [IGNOREEOF](https://www.gnu.org/software/bash/manual/bash.html#index-IGNOREEOF)


## 說明

在「Bash」這個「Shell」，有一個特性

當按下「`ctrl + d`」就會等同離開「bash」

也就是會關閉「terminal」。

所以我會做如下的設定，來避免按下「ctrl + d`」，就會關閉「terminal」。


## 設定檔案

* [~/.bashrc](https://github.com/samwhelp/bashrc-enhance-prototype/blob/main/prototype/start/debian/asset/overlay/etc/skel/.bashrc#L60)


## 如何設定

編輯「~/.bashrc」這個檔案，加入下面這一行

``` bash
set -o ignoreeof
```

做了這個設定之後，重新載入「`source ~/.bashrc`」。

爾後按下「`ctrl + d`」，就會顯示如下的訊息，並且出現下一個「命令列提示」。

```
Use "exit" to leave the shell.
```

也就是按下「`ctrl + d`」，不會關閉「terminal」。


## 完整範例

* [~/.bashrc](https://github.com/samwhelp/bashrc-enhance-prototype/blob/main/prototype/start/debian/asset/overlay/etc/skel/.bashrc#L60)
