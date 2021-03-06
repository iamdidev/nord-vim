<p align="center"><img src="https://cdn.rawgit.com/arcticicestudio/nord-vim/develop/assets/nord-vim-banner.svg"/></p>

<p align="center"><img src="https://assets-cdn.github.com/favicon.ico" width=24 height=24/> <a href="https://github.com/arcticicestudio/nord-vim/releases/latest"><img src="https://img.shields.io/github/release/arcticicestudio/nord-vim.svg"/></a> <a href="https://github.com/arcticicestudio/nord/releases/tag/v0.2.0"><img src="https://img.shields.io/badge/Nord-v0.2.0-blue.svg"/></a></p>

<p align="center">A arctic, north-bluish clean and elegant <a href="http://www.vim.org">Vim</a> color theme.</p>

<p align="center">Designed for a fluent and clear workflow.<br>
Based on the <a href="https://github.com/arcticicestudio/nord">Nord</a> color palette.</p>

---

Nord Vim is a 16 colorspace theme build to run in GUI- and terminal mode with support for many third-party plugins and styles for [lightline.vim](https://github.com/itchyny/lightline.vim) and  [vim-airline](https://github.com/vim-airline/vim-airline).

<p align="center"><img src="https://raw.githubusercontent.com/arcticicestudio/nord-vim/develop/assets/scrot-lang-javascript.png"/><br><blockquote>Font: <a href="https://adobe-fonts.github.io/source-code-pro">Source Code Pro</a> 20px</blockquote></p>

## Getting started
### Installation
**NOTE**: Nord Vim in terminal mode **MUST** be used with the associated terminal emulator theme in order to work properly!  
Make sure to install one of the currently supported terminal themes listed below **BEFORE** installing Nord Vim.

[![Nord GNOME Terminal](https://cdn.rawgit.com/arcticicestudio/nord/develop/src/assets/nord-gnome-terminal-banner.svg)](https://github.com/arcticicestudio/nord-gnome-terminal)  
[![Nord Guake](https://cdn.rawgit.com/arcticicestudio/nord/develop/src/assets/nord-guake-banner.svg)](https://github.com/arcticicestudio/nord-guake)  
[![Nord iTerm2](https://cdn.rawgit.com/arcticicestudio/nord/develop/src/assets/nord-iterm2-banner.svg)](https://github.com/arcticicestudio/nord-iterm2)  
[![Nord Konsole](https://cdn.rawgit.com/arcticicestudio/nord/develop/src/assets/nord-konsole-banner.svg)](https://github.com/arcticicestudio/nord-konsole)  
[![Nord Mintty](https://cdn.rawgit.com/arcticicestudio/nord/develop/src/assets/nord-mintty-banner.svg)](https://github.com/arcticicestudio/nord-mintty)  
[![Nord PuTTY](https://cdn.rawgit.com/arcticicestudio/nord/develop/src/assets/nord-putty-banner.svg)](https://github.com/arcticicestudio/nord-putty)  
[![Nord Terminal.app](https://cdn.rawgit.com/arcticicestudio/nord/develop/src/assets/nord-terminal-app-banner.svg)](https://github.com/arcticicestudio/nord-terminal-app)  
[![Nord Terminator](https://cdn.rawgit.com/arcticicestudio/nord/develop/src/assets/nord-terminator-banner.svg)](https://github.com/arcticicestudio/nord-terminator)  
[![Nord Terminix](https://cdn.rawgit.com/arcticicestudio/nord/develop/src/assets/nord-terminix-banner.svg)](https://github.com/arcticicestudio/nord-terminix)  
[![Nord Termite](https://cdn.rawgit.com/arcticicestudio/nord/develop/src/assets/nord-termite-banner.svg)](https://github.com/arcticicestudio/nord-termite)  
[![Nord XFCE Terminal](https://cdn.rawgit.com/arcticicestudio/nord/develop/src/assets/nord-xfce-terminal-banner.svg)](https://github.com/arcticicestudio/nord-xfce-terminal)  
[![Nord Xresources](https://cdn.rawgit.com/arcticicestudio/nord/develop/src/assets/nord-xresources-banner.svg)](https://github.com/arcticicestudio/nord-xresources)  

#### Via plugin/runtimepath manager
I recommend to use [`vim-plug`](https://github.com/junegunn/vim-plug).  
Add Nord Vim to your `.vimrc`
```sh
Plug 'arcticicestudio/nord-vim'
```
and install via `:PlugInstall`.

You can specify the `develop` branch to install the latest development version.  
```sh
Plug 'arcticicestudio/nord-vim', { 'branch': 'develop' }
```

A specific version can be installed via git tags.  
```sh
Plug 'arcticicestudio/nord-vim', { 'tag': 'v0.1.2' }
```

Of course it can be installed with any of your favorite tools:  
[`pathogen`](https://github.com/tpope/vim-pathogen)  
```sh
cd ~/.vim/bundle
git clone git://github.com/arcticicestudio/nord-vim.git
```

[`Vundle`](https://github.com/VundleVim/Vundle.vim)  
Add Nord Vim to your `.vimrc`
```sh
Plugin 'dracula/vim'
```
and install via `:PluginInstall`.

#### Manual
[Download](https://github.com/arcticicestudio/nord-vim/releases/latest) the latest version or clone the repository and copy the [`nord.vim`](https://github.com/arcticicestudio/nord-vim/blob/develop/colors/nord.vim) theme file to your `~/.vim/colors` directory.

### Activation
Use Nord Vim as your default color theme by adding it to your `.vimrc`
```sh
colorscheme nord
```
or change it on-the-fly by running `:colorscheme nord`.

[`vim-plug`](https://github.com/junegunn/vim-plug) also provides options to enable it on-demand for specific languages
```sh
" Activate Nord Vim when editing Java files
Plug 'arcticicestudio/nord-vim', { 'for': 'java' }
```
or on specific events.
```sh
" Activate Nord Vim when toggling the NERDTree
Plug 'arcticicestudio/nord-vim', { 'on':  'NERDTreeToggle' }
```

## Plugin Support
Nord Vim provides support for many third-party language- and the UI plugins.  

### UI Plugins
<p align="center"><a href="https://github.com/itchyny/lightline.vim">lightline</a><br><img src="https://raw.githubusercontent.com/arcticicestudio/nord-vim/develop/assets/scrot-plugin-support-ui-lightline.png"/><br><img src="https://raw.githubusercontent.com/arcticicestudio/nord-vim/develop/assets/scrot-plugin-support-ui-lightline-vsplit.png"/></p>

<p align="center"><a href="https://github.com/vim-airline/vim-airline">airline</a><br><img src="https://raw.githubusercontent.com/arcticicestudio/nord-vim/develop/assets/scrot-plugin-support-ui-airline.png"/><br><img src="https://raw.githubusercontent.com/arcticicestudio/nord-vim/develop/assets/scrot-plugin-support-ui-airline-vsplit.png"/></p>

<p align="center"><a href="https://github.com/airblade/vim-gitgutter">GitGutter</a><br><img src="https://raw.githubusercontent.com/arcticicestudio/nord-vim/develop/assets/scrot-plugin-support-ui-gitgutter.png"/></p>

<p align="center"><a href="https://github.com/scrooloose/nerdtree">NERDTree</a><br><img src="https://raw.githubusercontent.com/arcticicestudio/nord-vim/develop/assets/scrot-plugin-support-ui-nerdtree.png"/></p>

### Language Plugins
#### JavaScript
[`vim-javascript`](https://github.com/pangloss/vim-javascript)

Detailed descriptions for supported plugins can be found in the [project wiki](https://github.com/arcticicestudio/nord-vim/wiki).

## Languages
Nord Vim contains optimized styles to achieve a consistent and uniform coloring across languages.  
Detailed descriptions for supported languages can be found in the [project wiki](https://github.com/arcticicestudio/nord-vim/wiki) and in the [Plugin Support](#plugin-support) section.

![][scrot-lang-c]
![][scrot-lang-css]
![][scrot-lang-html]
![][scrot-lang-java]
![][scrot-lang-javascript]
![][scrot-lang-json]
![][scrot-lang-markdown]
![][scrot-lang-php]
![][scrot-lang-python]
![][scrot-lang-ruby]

## Development
[![](https://img.shields.io/badge/Changelog-0.1.2-blue.svg)](https://github.com/arcticicestudio/nord-vim/blob/v0.1.2/CHANGELOG.md) [![](https://img.shields.io/badge/Workflow-gitflow--branching--model-blue.svg)](http://nvie.com/posts/a-successful-git-branching-model) [![](https://img.shields.io/badge/Versioning-ArcVer_0.8.0-blue.svg)](https://github.com/arcticicestudio/arcver)

### Contribution
Please report issues/bugs, feature requests and suggestions for improvements to the [issue tracker](https://github.com/arcticicestudio/nord-vim/issues).

<p align="center"><img src="https://cdn.rawgit.com/arcticicestudio/nord/develop/src/assets/banner-footer-mountains.svg" /></p>

<p align="center"> <img src="http://arcticicestudio.com/favicon.ico" width=16 height=16/> Copyright &copy; 2016 Arctic Ice Studio</p>

<p align="center"><a href="http://www.apache.org/licenses/LICENSE-2.0"><img src="https://img.shields.io/badge/License-Apache_2.0-blue.svg"/></a> <a href="https://creativecommons.org/licenses/by-sa/4.0"><img src="https://img.shields.io/badge/License-CC_BY--SA_4.0-blue.svg"/></a></p>

[scrot-readme-default-profile]: https://raw.githubusercontent.com/arcticicestudio/nord-vim/develop/src/assets/scrot-readme-default-profile.png
[scrot-readme-lazy-profile-change]: https://raw.githubusercontent.com/arcticicestudio/nord-vim/develop/src/assets/scrot-readme-lazy-profile-change.png

[scrot-lang-c]: https://raw.githubusercontent.com/arcticicestudio/nord-vim/develop/assets/scrot-lang-c.png
[scrot-lang-css]: https://raw.githubusercontent.com/arcticicestudio/nord-vim/develop/assets/scrot-lang-css.png
[scrot-lang-html]: https://raw.githubusercontent.com/arcticicestudio/nord-vim/develop/assets/scrot-lang-html.png
[scrot-lang-java]: https://raw.githubusercontent.com/arcticicestudio/nord-vim/develop/assets/scrot-lang-java.png
[scrot-lang-javascript]: https://raw.githubusercontent.com/arcticicestudio/nord-vim/develop/assets/scrot-lang-javascript.png
[scrot-lang-json]: https://raw.githubusercontent.com/arcticicestudio/nord-vim/develop/assets/scrot-lang-json.png
[scrot-lang-markdown]: https://raw.githubusercontent.com/arcticicestudio/nord-vim/develop/assets/scrot-lang-markdown.png
[scrot-lang-php]: https://raw.githubusercontent.com/arcticicestudio/nord-vim/develop/assets/scrot-lang-php.png
[scrot-lang-python]: https://raw.githubusercontent.com/arcticicestudio/nord-vim/develop/assets/scrot-lang-python.png
[scrot-lang-ruby]: https://raw.githubusercontent.com/arcticicestudio/nord-vim/develop/assets/scrot-lang-ruby.png
