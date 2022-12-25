# 配置 Mac 新系统

把家里的 Mac 重置了，把新系统的配置过程分享一下。

1. 登录 Apple 账号并同步
2. 安装 Chrome 并同步
    1. [Chrome](https://www.google.cn/chrome/index.html)
    2. 登录 Google 账号并同步 
    3. 遇到登陆失败
    4. 下载 [SwitchyOmega crx](https://github.com/FelisCatus/SwitchyOmega/releases) 并拖入[拓展程序页](chrome://extensions)
    5. [百度 PAC](http://pac.internal.baidu.com/bdnew.pac)（仅限百度员工使用）
3. [HomeBrew 国内镜像](https://gitee.com/cunkai/HomebrewCN)
4. Shell
    1. [iterm2](https://iterm2.com)
    2. [Oh My Zsh](https://github.com/ohmyzsh/ohmyzsh)
    3. [zsh-autocomplete](https://github.com/marlonrichert/zsh-autocomplete)
    4. [zsh-nvm](https://github.com/lukechilds/zsh-nvm)
    5. plugins=(git z zsh-autosuggestions zsh-nvm)
    6. [autojump](https://github.com/wting/autojump) `brew install autojump`
5. 开发环境
    1. `nvm install --lts`
    2. [yarn](https://yarnpkg.com/getting-started/install)
6. [SourceTree](https://www.sourcetreeapp.com)
7. IDE
    1. [JetBrains Toolbox App](https://www.jetbrains.com/toolbox-app/)
    2. 用 Toolbox 安装 WebStorm
    3. 启动同步