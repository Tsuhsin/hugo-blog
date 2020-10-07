---
title: "安裝 z-shell"
date: 2019-10-01T14:38:44+08:00
categories:
  - "技術"
draft: false
tags:
  - "z-shell"
author: "Tsuhsin"
---
# 安裝 z-shell
如果沒有brew的話要先安裝 `brew`

安裝 `brew`
```
ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"
```

安裝 `zsh`
```
brew install zsh
```
安裝 `oh-my-zsh`
```
sh -c "$(curl -fsSL https://raw.github.com/robbyrussell/oh-my-zsh/master/tools/install.sh)"
```
> zsh 的設定檔放在`~/.zshrc`，這個檔案需要我們自己產生由於我們用`oh-my-zsh`，所以這邊建議使用 `oh-my-zsh` 預設的 templete 比較省事

```
cp ~/.oh-my-zsh/templates/zshrc.zsh-template ~/.zshrc
```
修改預設的 shell 為 `zsh`
```
chsh -s /usr/local/bin/zsh
```
