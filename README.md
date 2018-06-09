# Install components 

## Vim

### For MAC OS
```
$ brew install git ctags
```

### Linux

* Ubuntu\Debian

```
$ sudo apt-get install git exuberant-ctags ncurses-term curl
```

* Gentoo
```
$ sudo emerge --ask dev-util/ctags sys-libs/ncurses dev-vcs/git dev-python/pyflakes net-misc/curl
```

* Arch Linux via *pacman* (recomend used *pacaur*)
```
$ sudo pacman -S git-core ctags ncurses curl
```
* Fedora

```
$ sudo dnf install ncurses-devel git ctags-etags curl
```

* openSUSE
```
$ sudo zypper in ncurses-devel git ctags curl
```

### Fast-installation by URL parameters

Vim-bootstrap generator can accept URL params via request as example below.

    curl 'https://raw.githubusercontent.com/nicksonet/bashrc/master/.vimrc' > ~/.vimrc


### Python bundle (optionally)

* pyflakes
* jedi
* neovim (neovim only) 

```
$ pip install flake8 jedi
$ pip2 install --user --upgrade neovim
$ pip3 install --user --upgrade neovim
```

### Elm bundle (optionally)

* elm-test
* elm-oracle
* elm-format

```
$ npm install -g elm-test
$ npm install -g elm-oracle
$ npm install -g elm-format@exp

```


## Commands
</summary>
<details>
<summary>:black_small_square: Basic Commands</summary>

Commands | Descriptions
--- | ---
`:cd <path>` | Open path */path*
<kbd>Ctrl</kbd><kbd>w</kbd>+<kbd>h</kbd><kbd>j</kbd><kbd>k</kbd><kbd>l</kbd> | Navigate via split panels
<kbd>Ctrl</kbd><kbd>w</kbd><kbd>w</kbd> | Alternative navigate vim split panels
<kbd>,</kbd><kbd>.</kbd> | Set path working directory
<kbd>,</kbd><kbd>w</kbd> or <kbd>,</kbd><kbd>x</kbd> | Next buffer navigate
<kbd>,</kbd><kbd>q</kbd> or <kbd>,</kbd><kbd>z</kbd> | previous buffer navigate
<kbd>shift</kbd><kbd>t</kbd> | Create a tab
<kbd>tab</kbd> | next tab navigate
<kbd>shift</kbd><kbd>tab</kbd> | previous tab navigate
<kbd>,</kbd><kbd>e</kbd> | Find and open files
<kbd>,</kbd><kbd>b</kbd> | Find file on buffer (open file)
<kbd>,</kbd><kbd>c</kbd> | Close active buffer (clone file)
<kbd>F2</kbd>  | Open tree navigate in actual opened file
<kbd>F3</kbd>  | Open/Close tree navigate files
<kbd>F4</kbd> | List all class and method, support for python, go, lua, ruby and php
<kbd>,</kbd><kbd>v</kbd> | Split vertical
<kbd>,</kbd><kbd>h</kbd> | Split horizontal
<kbd>,</kbd><kbd>f</kbd> | Search in the project
<kbd>,</kbd><kbd>o</kbd> | Open github file/line (website), if used git in **github**
<kbd>,</kbd><kbd>s</kbd><kbd>h</kbd> | Open shell.vim terminal inside Vim or NeoVim built-in terminal
<kbd>,</kbd><kbd>g</kbd><kbd>a</kbd> | Execute *git add* on current file
<kbd>,</kbd><kbd>g</kbd><kbd>c</kbd> | git commit (splits window to write commit message)
<kbd>,</kbd><kbd>g</kbd><kbd>s</kbd><kbd>h</kbd> | git push
<kbd>,</kbd><kbd>g</kbd><kbd>l</kbd><kbd>l</kbd> | git pull
<kbd>,</kbd><kbd>g</kbd><kbd>s</kbd> | git status
<kbd>,</kbd><kbd>g</kbd><kbd>b</kbd> | git blame
<kbd>,</kbd><kbd>g</kbd><kbd>d</kbd> | git diff
<kbd>,</kbd><kbd>g</kbd><kbd>r</kbd> | git remove
<kbd>,</kbd><kbd>s</kbd><kbd>o</kbd> | Open Session
<kbd>,</kbd><kbd>s</kbd><kbd>s</kbd> | Save Session
<kbd>,</kbd><kbd>s</kbd><kbd>d</kbd> | Delete Session
<kbd>,</kbd><kbd>s</kbd><kbd>c</kbd> | Close Session
<kbd>></kbd> | indent to right
<kbd><</kbd> | indent to left
<kbd>g</kbd><kbd>c</kbd> | Comment or uncomment lines that {motion} moves over
<kbd>Y</kbd><kbd>Y</kbd> | Copy to clipboard
<kbd>,</kbd><kbd>p</kbd> | Paste
<kbd>Ctrl</kbd><kbd>y</kbd> + <kbd>,</kbd> | Activate Emmet plugin
</details>

<details>
<summary>:black_small_square: Python hotkeys</summary>

Commands | Descriptions
--- | ---
`SHIFT+k` | Open documentation
`Control+Space` | Autocomplete
`,d` | Go to the Class/Method definition
`,r` | Rename object definition
`,n` | Show where command is usage
</details>

<details>
<summary>:black_small_square: Ruby hotkeys</summary>

Commands | Descriptions
------- | -------
`,a`        | Run all specs
`,l`        | Run last spec
`,t`        | Run current spec
`,rap`        | Add Parameter
`,rcpc`     | Inline Temp
`,rel`        | Convert Post Conditional
`,rec`        | Extract Constant          (visual selection)
`,rec`       | Extract to Let (Rspec)
`,relv`     | Extract Local Variable    (visual selection)
`,rrlv`     | Rename Local Variable     (visual selection/variable under the cursor)
`,rriv`     | Rename Instance Variable  (visual selection)
`,rem`      | Extract Method            (visual selection)

</details>

## Learn Vim

Visit the following sites to learn more about Vim:

* [Learn Vim Progressively](http://yannesposito.com/Scratch/en/blog/Learn-Vim-Progressively/)
* [Vim Adventures](http://vim-adventures.com/)
* [Vimcasts](http://vimcasts.org)
* [Using Vim as a Complete Ruby on Rails IDE](http://biodegradablegeek.com/2007/12/using-vim-as-a-complete-ruby-on-rails-ide/)
* [Why, oh WHY, do those #?@! nutheads use vi?](http://www.viemu.com/a-why-vi-vim.html)
* [Byte of Vim](http://www.swaroopch.com/notes/Vim)
* [Screencast "17 tips for Vim" (in portuguese)](http://blog.lucascaton.com.br/?p=1081)
* [MinuteVim Tricks](https://www.youtube.com/user/MinuteVimTricks)
* [Join the Church of Vim, and you too can be a saint!](http://www.avelino.xxx/2015/03/church-vim)
* [Vim para noobs (in portuguese)](https://woliveiras.com.br/vimparanoobs/)
* [Vimbook (in portuguese)](https://cassiobotaro.gitbooks.io/vimbook/content/)
