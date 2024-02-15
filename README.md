# dotfiles

A place where I can store all the dotfiles I use for my machines and/or projects.

## Dependencies

### Homebrew

https://brew.sh/

```sh
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
```

### Stow

https://www.gnu.org/software/stow/

```sh
brew install stow
```

## Install
Clone this repository to `$HOME` directory
```sh
cd ~
git clone git@github.com:johnzanussi/dotfiles.git
```

Run `stow` to create symlinks.

```
stow .
```

## License

MIT / BSD
