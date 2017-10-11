# 256 xterm colors

256 xterm colors is a small script to show all 256 colors in your terminal.
If you are on a Mac, [iTerm2](https://www.iterm2.com/) has beautiful color support.

## How to run

Simply copy this into your terminal, it will download and show 256 pretty colors with a single command:

```
/usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/gawin/bash-colors-256/master/256-xterm-colors)"
```

## Example screenshot

![Screenshot](https://raw.githubusercontent.com/gawin/bash-colors-256/master/bash_256_colors_iterm_screenshot.png?raw=true)

## Common issues

Please make sure that you exported your TERM as xterm-256color. You may add this line in your `~/.profile` or `~/.bashrc` configuration.

```
export TERM=xterm-256color
```

You can easily verify if the TERM variable is set correctly using this command:

```
echo $TERM
```

## License

MIT License. Copyright 2011-2017 Gawin. [https://gaw.in](https://gaw.in)
