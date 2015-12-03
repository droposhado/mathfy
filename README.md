# mathfy

Theme based on [norm](https://github.com/robbyrussell/oh-my-zsh/blob/master/themes/norm.zsh-theme)

Modifications:

 - Username
 - Hour, minutes and seconds
 - Full current path
 - Some colors have been changed to white

Format is:

```
computer λ user . HH:mm:ss /full/current/path →
```

With git:

```
computer λ user . HH:mm:ss /full/current/path → λ git branch →
```

### How to install

- Clone this repo:

```
$ git clone https://github.com/flavertonrr/mathfy.git ~/.mathfy
```

- Create a link to file using

```
$ ln -s ~/.mathfy/mathfy.zsh-theme ~/.oh-my-zsh/themes/mathfy.zsh-theme
```

- Go to `~/.zshrc` and change variable `ZSH_THEME` to:

```
ZSH_THEME="mathfy"
```

### License

Available in [license file](LICENSE.md)
