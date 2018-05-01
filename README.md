# configs
vimrc, dotfiles and other shit

## vim

Copy `vimrc` file to `$HOME`:

```shell
cp vimrc ~/.vimrc
```

You can also retrieve it from [https://javuto.net/vimrc](https://javuto.net/vimrc):

```shell
wget -O ~/.vimrc https://javuto.net/vimrc
```

## vscode

Install Visual Studio Code from [https://code.visualstudio.com/Download](https://code.visualstudio.com/Download)

`Code > Preferences > Settings > User Settings`

## iterm2

Install iTerm2 from [https://www.iterm2.com/downloads.html](https://www.iterm2.com/downloads.html)

Import settings: `iTerm2 > Preferences > General > Load preferences from a custom folder or URL`

## zsh

Install `oh-my-zsh` from [https://github.com/robbyrussell/oh-my-zsh](https://github.com/robbyrussell/oh-my-zsh):

```shell
sh -c "$(curl -fsSL https://raw.githubusercontent.com/robbyrussell/oh-my-zsh/master/tools/install.sh)"
```

Enable custom configuration:

```shell
cp zshrc ~/.zshrc
```

Done.