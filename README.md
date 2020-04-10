# switch
Switch DNS for pre env

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

#### [Oh-My-Zsh](http://ohmyz.sh/)

1. 终端执行：
```bash
# 注意，需要切换到小鱼私有npm镜像地址
$ git clone ssh://git@10.172.94.171:10022/frontend/xian/switch.git $ZSH_CUSTOM/plugins/switch
```
2. Edit `~/.zshrc`:
  ```bash
  ...
  plugins=(... switch)
  ```
3. Reload source:`source .zshrc`

#### Update
```bash
$ rm -rf $ZSH_CUSTOM/plugins/switch && git clone ssh://git@10.172.94.171:10022/frontend/xian/switch.git $ZSH_CUSTOM/plugins/switch
```

## Less is more
Super simple open method：

```sh
# config oh-my-zsh alias
$ alias set="switch"
```
then `set -p` to change pre env..
