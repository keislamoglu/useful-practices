# Useful Practices

## Markdown to PDF:

1. install grip

```zsh
pip install grip
```

2. convert md file into html

```zsh
grip markdownfile.md --export markdownfile.html
```

3. install wkhtmltopdf (for OS X)

```zsh
brew install Caskroom/cask/wkhtmltopdf
```

4. convert html file into pdf

```zsh
wkhtmltopdf markdownfile.html markdownfile.pdf
```


## Make terminal looks better
1. Install zsh if needed

```zsh
brew install zsh
```

2. Install Oh My Zsh

```zsh
sh -c "$(curl -fsSL https://raw.github.com/robbyrussell/oh-my-zsh/master/tools/install.sh)"
```

3. Install PowerLevel10k theme

```zsh
git clone https://github.com/romkatv/powerlevel10k.git $ZSH_CUSTOM/themes/powerlevel10k
```

4. Enable the theme by changing `ZSH_THEME` value in `~/.zshrc` file.

```zsh
ZSH_THEME="powerlevel10k/powerlevel10k"
```

5. If not installed yet, install **MesloLGF NF** font manually

[https://github.com/romkatv/powerlevel10k#manual-font-installation](https://github.com/romkatv/powerlevel10k#manual-font-installation)
