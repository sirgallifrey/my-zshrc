# Installing

Your ~/.zshrc file must be empty, otherwise it will be overwritten. So backup it.

## if you are

```
git clone git@github.com:sirgallifrey/my-zshrc.git ~/zshrc
git clone https://github.com/zsh-users/antigen.git ~/antigen
echo "source ./zshrc/zshrc" > ~/.zshrc
```

## if you are not me, but somehow want this zshconfig...

```
git clone https://github.com/sirgallifrey/my-zshrc.git ~/zshrc
git clone https://github.com/zsh-users/antigen.git ~/antigen
echo "source ./zshrc/zshrc" > ~/.zshrc
```


This zsh config will source three files: ~/.zsh_functions ~/.zsh_aliases and ~/.zsh_custom in that order.
Use them to make your custom configs and changes.


### Contributions

This repo is made for my own personal use, but anyone can use it if want to. So issues and PRs will be taken into account, but I will not make changes that do not conform to what I want. For that you are welcome to copy and make your own changes in some other repo. :D
