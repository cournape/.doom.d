# .doom.d
my emacs doom config

## Some installation/setup details

### MacOS

As of May 2022, I install everything in native homebrew, including emacs,
iterm2, etc.

#### iterm2 and terminal stuff

I use iterm2 as my main terminal. To use option key as meta, you need to edit
iterm2 profile section.

To be able to use emacs inside the terminal, make sure to use `emacs -nw`. I
alias as follows in my .zshrc:

```
alias emacs="emacs -nw"
```
