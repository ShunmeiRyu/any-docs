# Mac 终端主题基本配置 

- oh my zsh
- powerlevel10k
- zsh-autosuggestions
- zsh-syntax-highlighting

## oh my zsh
```
sh -c "$(curl -fsSL https://raw.githubusercontent.com/ohmyzsh/ohmyzsh/master/tools/install.sh)" "" --unattended
```

## powerlevel10k
> 个人比较喜欢，您可以根据跟人风格选其他主题。

```
git clone --depth=1 https://github.com/romkatv/powerlevel10k.git ${ZSH_CUSTOM:-$HOME/.oh-my-zsh/custom}/themes/powerlevel10k
```
编辑`~/.zshrc`文件 ZSH_THEME="robbyrussell" ==>　ZSH_THEME="powerlevel10k/powerlevel10k"。
