# switch
Switch dns for pre env

## SYNOPSIS

```sh
$ switch [--options]
```

## OPTIONS

```sh
# switch default dns env
$ switch
```

```sh
# switch pre env
$ switch -p
```

## Installation

### Basic install

The preferred way of installation is to simply add the `switch` script
somewhere into your path (e.g. add the directory to your `PATH` environment
or copy `switch` into an existing included path like `/usr/local/bin`).

#### [Oh-My-Zsh](http://ohmyz.sh/)

1. 终端执行：
```bash
$ git clone git@github.com:luojinghui/switch.git $ZSH_CUSTOM/plugins/switch
```
2. Edit `~/.zshrc`:
  ```bash
  ...
  plugins=(... switch)
  ```
3. Reload source:`source .zshrc`


## Less is more
Super simple open method：

```sh
# config oh-my-zsh alias
$ alias set="switch"
```
then `set -p` to change pre env..