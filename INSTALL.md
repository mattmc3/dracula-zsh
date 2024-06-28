### [Zsh](http://zsh.org/)

#### Install using Git

If you are a git user, you can install the theme by cloning the repo:

    git clone https://github.com/dracula/zsh.git ${ZSH_CUSTOM:=$HOME/.oh-my-zsh/custom}/themes/dracula

Then, create a symbolic link in [oh-my-zsh](https://github.com/ohmyzsh/ohmyzsh/)'s custom theme folder:

    ln -s $ZSH_CUSTOM/themes/dracula/dracula.zsh-theme $ZSH_CUSTOM/themes

_P.S.: Remember Oh-My-Zsh should have already set `$ZSH_CUSTOM` for you, but if you want to use a different location you can update that variable in your .zshrc. You can
learn more about customization [here](https://github.com/ohmyzsh/ohmyzsh/wiki/Customization)._

#### Install manually

1.  Download using the [GitHub .zip download](https://github.com/dracula/zsh/archive/master.zip) option and unzip them.
2.  Move `dracula.zsh-theme` file to [oh-my-zsh](https://github.com/ohmyzsh/ohmyzsh)'s custom theme folder: `~/.oh-my-zsh/custom/themes/dracula.zsh-theme`.
3.  Move `/lib` to [oh-my-zsh](https://github.com/ohmyzsh/ohmyzsh)'s custom theme folder: `~/.oh-my-zsh/custom/themes/lib`.

#### Activating theme

Go to your `~/.zshrc` file and set `ZSH_THEME="dracula"`.

#### Install using [antidote](https://github.com/mattmc3/antidote)

Just add `dracula/zsh` to your `~/.zsh_plugins.txt` file.

#### Install using [zplug](https://github.com/zplug/zplug)

Just add `zplug "dracula/zsh", as:theme` to your `~/.zshrc` file.
