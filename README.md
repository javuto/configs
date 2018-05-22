# configs
vimrc, dotfiles and other shit

## brew

Check [https://brew.sh/](https://brew.sh/) for more instructions but basically:

```shell
/usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"
```

## wget

Install `wget` using brew:

```shell
brew install wget
```

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

To list all the installed extensions run:

```shell
$ /Applications/Visual\ Studio\ Code.app/Contents/Resources/app/bin/code --list-extensions
```

To install the extensions in a text file, run:

```shell
for i in $(cat extensions.txt)
do 
  /Applications/Visual\ Studio\ Code.app/Contents/Resources/app/bin/code --install-extension $i
done
```

## iterm2

Install iTerm2 from [https://www.iterm2.com/downloads.html](https://www.iterm2.com/downloads.html)

Import settings: `iTerm2 > Preferences > General > Load preferences from a custom folder or URL`

You will need to add the powerline fonts, you can find them in [https://github.com/powerline/fonts](https://github.com/powerline/fonts) in the `fonts` directory.

## zsh

Install `oh-my-zsh` from [https://github.com/robbyrussell/oh-my-zsh](https://github.com/robbyrussell/oh-my-zsh):

```shell
sh -c "$(curl -fsSL https://raw.githubusercontent.com/robbyrussell/oh-my-zsh/master/tools/install.sh)"
```

Copy the themes folder:

```shell
cp -R themes ~/.oh-my-zsh
```

Enable custom configuration:

```shell
cp zshrc ~/.zshrc
```

## karabiner

Install Karabiner-Elements from [https://github.com/tekezo/Karabiner-Elements](https://github.com/tekezo/Karabiner-Elements)

```shell
cp karabiner.json ~/.config/karabiner
```

## Random apps

[http://member.ipmu.jp/yuji.tachikawa/MenuMetersElCapitan/](http://member.ipmu.jp/yuji.tachikawa/MenuMetersElCapitan/)

[https://github.com/Clipy/Clipy](https://github.com/Clipy/Clipy)

[https://github.com/eczarny/spectacle](https://github.com/eczarny/spectacle)

[https://www.vagrantup.com/downloads.html](https://www.vagrantup.com/downloads.html)

[https://www.virtualbox.org/wiki/Downloads](https://www.virtualbox.org/wiki/Downloads)

[https://www.obdev.at/products/littlesnitch/download.html](https://www.obdev.at/products/littlesnitch/download.html)

Done.
