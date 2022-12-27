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
8. [ShiftIt](https://github.com/fikovnik/ShiftIt)

## 软件简单介绍

- [SourceTree](https://www.sourcetreeapp.com/)，git 历史的可视化，并且可以完成大部分简单的操作。

- [iterm2](https://iterm2.com/) + [oh-my-zsh](https://github.com/robbyrussell/oh-my-zsh) + [autosuggestion](https://github.com/zsh-users/zsh-autosuggestions)，比较多用的两个 plugin 是快速跳转 `z`，和自动补全。

- [Chrome](https://www.google.com/chrome/)，前端必用，善用插件，善用调试工具，后面会说。

- [WebStorm](https://www.jetbrains.com/webstorm/)，WebStorm 是主力，也有特别多定制，后面会说。

- [如流](https://infoflow.baidu.com/)，工作沟通。

- [Microsoft Office](https://www.office.com/)，公司的，最常使用的是 PowerPoint，善用母版。

- [ShiftIt](https://github.com/fikovnik/ShiftIt)，可以快捷键控制窗口布局，`⌃⌥⌘→` 就是把当前窗口占据右边半屏这样。我不喜欢 Mac 的最大化，所以选用了这个方案。

## 配置

大部分都同步了，一些配置技巧查看[快捷键](https://github.com/dancerphil/awesome/blob/master/Keymap.md)篇。
