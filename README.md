[![Slack Room][slack-badge]][slack-link]

# command-not-found

⁉ Fish plugin for a project which tries to reproduce Ubuntu’s [command-not-found](https://github.com/Homebrew/homebrew-command-not-found) for Homebrew users on *OS X* (only!).

> On Ubuntu, when you try to use a command that doesn’t exist locally but is available through a package, Bash will suggest you a command to install it.

## Install

With [fisherman]

```fish
$ fisher command_not_found
```

## Features

```
$ tree
The program 'tree' is currently not installed. You can install it by typing:
  brew install tree
$ brew install tree
==> Downloading https://homebrew.bintray.com/bottles/tree-1.7.0.el_capitan.bottle.1.tar.gz
######################################################################## 100.0%
==> Pouring tree-1.7.0.el_capitan.bottle.1.tar.gz
🍺  /usr/local/Cellar/tree/1.7.0: 7 files, 113.1K
```

[slack-link]: https://fisherman-wharf.herokuapp.com/
[slack-badge]: https://fisherman-wharf.herokuapp.com/badge.svg

[fisherman]: https://github.com/fisherman/fisherman
