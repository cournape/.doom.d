# .doom.d
my emacs doom config

## Some installation/setup details

### MacOS

As of May 2022, I install everything in native (arm64) homebrew, including
emacs, iterm2, etc. and it seems to work.

#### iterm2 and terminal stuff

I use iterm2 as my main terminal. To use option key as meta, you need to edit
iterm2 profile section.

To be able to use emacs inside the terminal, make sure to use `emacs -nw`. I
alias as follows in my .zshrc:

``` shell
alias emacs="emacs -nw"
```

To support `vterm` package for term emulation

``` shell
brew install libvterm
```

#### Language / packages specific information

To support Rust:

``` shell
rustup component add rust-src
brew install rust-analyzer
```
