# mac-setup

## oh my zsh
https://ohmyz.sh/

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

```bash
export VISUAL=vim
export EDITOR="$VISUAL"
```

in ~/.bash_profile

## GNU Command Line Tools
```bash
brew install coreutils
```

```bash
brew install binutils
brew install diffutils
brew install ed
brew install findutils
brew install gawk
brew install gnu-indent
brew install gnu-sed
brew install gnu-tar
brew install gnu-which
brew install gnutls
brew install grep
brew install gzip
brew install screen
brew install watch
brew install wdiff
brew install wget
```

## non-GNU Command Line Tools
```bash
brew install tree
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
brew install vim
brew install macvim
brew install zsh
```

## JDK
```bash
brew install jenv
```

## iTerm2
```bash
brew cask install iterm2
```

## PostgreSQL Client
```
brew install libpq
```
