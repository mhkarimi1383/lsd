# LSD
LSD (The next gen ls command) Configuration (Based on dracula theme)

## Installation

> Before getting started, backup your current configuration

Run the command below and you are good to go

```bash
git clone https://github.com/mhkarimi1383/lsd ~/.config/lsd
```

**Recommended**: Add following aliases to your `bashrc` or `zshrc`

```bash
alias dir="ls"
command -v lsd > /dev/null && alias ls='lsd -h --group-dirs first'
command -v lsd > /dev/null && alias tree='lsd --tree'
```
