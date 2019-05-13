# mac-setup

## Setting up Homebrew
[Hombrew Homepage](https://brew.sh/)

[Add shell completion](https://docs.brew.sh/Shell-Completion)

## Git
```bash
brew install git
```

```bash
git config --global user.name "Your Name"
git config --global user.email "you@your-domain.com"
git config --global color.ui auto
```

## Editor

export EDITOR="vim" in ~/.bash_profile

## GNU Command Line Tools
```bash
brew install coreutils
```

```bash
brew install binutils
brew install diffutils
brew install ed --with-default-names
brew install findutils --with-default-names
brew install gawk
brew install gnu-indent --with-default-names
brew install gnu-sed --with-default-names
brew install gnu-tar --with-default-names
brew install gnu-which --with-default-names
brew install gnutls
brew install grep --with-default-names
brew install gzip
brew install screen
brew install watch
brew install wdiff --with-gettext
brew install wget
```

## Update existing GNU tools
```bash
brew install bash
brew install emacs
brew install gdb  # gdb requires further actions to make it work. See `brew info gdb`.
brew install gpatch
brew install less
brew install m4
brew install make
brew install nano
```

## Update existing non-GNU tools
```bash
brew install file-formula
brew install git
brew install openssh
brew install perl
brew install python
brew install rsync
brew install svn
brew install unzip
brew install vim --override-system-vi
brew install macvim --with-override-system-vim
brew install zsh
```
