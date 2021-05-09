# fish-read-silent

Basic port of bash's `read -s` command to silently read sensitive input.

### Install

Install with your favourite fish package manager, such as [fisherman] or [oh-my-fish]

```shell
# Install with fisher v4
fisher install dideler/fish-read-silent

# Install with fisher v3
fisher add dideler/fish-read-silent

# Install with fisher v2
fisher install dideler/fish-read-silent

# Install with oh-my-fish
omf install https://github.com/dideler/fish-read-silent
```

### Usage

```
read_silent --help
read_silent secret
read_silent --prompt="Secret ▶ " secret
```


[fisherman]: https://github.com/fisherman/fisherman
[oh-my-fish]: https://github.com/oh-my-fish/oh-my-fish
