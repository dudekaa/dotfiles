# My personal dotfiles
## Requirements

  * [dotdrop](https://github.com/deadc0de6/dotdrop) for dotfiles managing. Available as [submodule](dotdrop), but still needs to be [installed](https://dotdrop.readthedocs.io/en/latest/installation/#as-a-submodule).
  * [bash](https://www.gnu.org/software/bash/) as default shell
  * [gbt](https://github.com/jtyr/gbt) in *$PATH*

## Configures

  * [bat](https://github.com/sharkdp/bat) - A cat(1) clone with syntax highlighting and Git integration.
  * [mdv](https://github.com/axiros/terminal_markdown_viewer) - Terminal markdown viewer
  * [vim](https://www.vim.org/) - Vi IMproved
  * [yarn-completion](https://github.com/dsifford/yarn-completion) - yarn v1 bash 4+ completion

## Install on new machine
```bash
$ git clone "https://github.com/dudekaa/dotfiles.git"
$ git submodule update --init
$ pip3 install --user -r dotdrop/requirements.txt
$ ./dotdrop/bootstrap.sh
$ ./dotdrop.sh install
```

NOTE: There's `dotdrop` alias in `~/.bashrc` that needs updating according to git repository clone path.
