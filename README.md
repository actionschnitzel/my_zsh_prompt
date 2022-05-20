# my_zsh_prompt
    
#### Just for me to remember how I did it :-P



<img src="https://github.com/actionschnitzel/my_zsh_prompt/blob/main/My_ZSH_Prompt.png" width="500">
## Base Install

```
sudo apt update    
    
sudo apt install zsh
    
echo $0 #checks what shell
    
chsh # Change shell to /bin/zsh
    
reboot
```


## Install Fonts
Set Terminal Font to:
#### "MesloLGS NF Regular"

## Install Oh My ZSH

```
sh -c "$(curl -fsSL https://raw.github.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"
```

## Install powerlevel10k
```
git clone --depth=1 https://github.com/romkatv/powerlevel10k.git ${ZSH_CUSTOM:-$HOME/.oh-my-zsh/custom}/themes/powerlevel10k

nano ~/.zshrc
```
replace:
`
ZSH_THEME="what ever was here"
`
with:
`
ZSH_THEME="powerlevel10k/powerlevel10k".
`
    
Close the Terminal and reopen. The Config tool start automaticly.    

Select what you like.

If you want to change the theming typ:
`
p10k configure
`


