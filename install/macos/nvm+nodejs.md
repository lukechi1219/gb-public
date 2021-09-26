---
description: 這邊要注意不支援 Homebrew 來安裝，避免出現問題
---

# nvm + nodejs

移除舊版的 nodejs

[https://askubuntu.com/questions/873811/how-to-uninstall-node-local-issue](https://askubuntu.com/questions/873811/how-to-uninstall-node-local-issue)

[https://stackabuse.com/how-to-uninstall-node-js-from-mac-osx/](https://stackabuse.com/how-to-uninstall-node-js-from-mac-osx/)

.

[https://github.com/nvm-sh/nvm\#installing-and-updating](https://github.com/nvm-sh/nvm#installing-and-updating)

[https://hsiangfeng.github.io/nodejs/20200124/3404456418/](https://hsiangfeng.github.io/nodejs/20200124/3404456418/)

nvm 是幫我們管理 Nodejs 版本的工具，安裝在 Mac 環境會稍微麻煩一點，不像 Windows 有專屬的安裝包那麼簡單。

```text
curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.38.0/install.sh | bash
```

```text
pwd

more .zshrc
```

如果在 Big Sur 的 zsh 要能正常使用 nvm 的話 , 在 .zshrc 裡面應該要有下面三行設定

```text
export NVM_DIR="$HOME/.nvm"

# This loads nvm
[ -s "$NVM_DIR/nvm.sh" ] && \. "$NVM_DIR/nvm.sh"  

# This loads nvm bash_completion
[ -s "$NVM_DIR/bash_completion" ] && \. "$NVM_DIR/bash_completion"
```

檢查 nvm 是否順利安裝成功  
可以使用以下指令：

```text
command -v nvm
```

安裝 nodejs \( LTS: long term support , 代表 最穩定的版本 \)

```text
nvm install --lts
```

檢查安裝版本

```text
nvm list
```

```text
->     v14.16.0
         system
default -> v14.16.0
iojs -> N/A (default)
unstable -> N/A (default)
node -> stable (-> v14.16.0) (default)
stable -> 14.16 (-> v14.16.0) (default)
```

.

