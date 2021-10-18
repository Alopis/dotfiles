# dotfiles

My dotfiles managed by chezmoi

## first time set up

```sh
chezmoi --source ~/Code/repos/alopis/dotfiles init --apply alopis
```

## if chezmoi is not installed

```sh
sh -c "$(curl -fsLS git.io/chezmoi)" -- init --apply alopis --source ~/Code/repos/alopis/dotfiles
```