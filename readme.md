# Zsh self completions

`zsh-self-completions` is a fix for completions in zsh that allows bash-like
`complete -C` completions in zsh. This enables the command line programs to
provide their own completions. This also reduces the startup time of zsh by
delegating the completions to the command line program itself at completion
request.

- Read `COMP_*` environment variables and `complete -C` documentation:
[bash manpage](https://www.man7.org/linux/man-pages/man1/bash.1.html)
