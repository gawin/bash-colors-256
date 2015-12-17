# 256 xterm colors

256 xterm colors is a small script to show all 256 colors in your terminal.
If you are on a Mac, [iTerm2](https://www.iterm2.com/) has beautiful color support.

## Installation

Please make sure that you exported your TERM as xterm-256color. You may add this line in your `~/.profile` or `~/.bashrc` configuration.

```
export TERM=xterm-256color
```

You can easily verify if the TERM variable is set correctly using this command:

```
echo $TERM
```

## Getting started

```
ruby 256-xterm-colors
```

or you can add the execution bits to make 256-xterm-colors executable

```
chmod +x 256-xterm-colors
./256-xterm-colors
```

## Example

![Screenshot](https://raw.githubusercontent.com/gawin/bash-colors-256/master/bash_256_colors_iterm_screenshot.png?raw=true)

## License

MIT License. Copyright Gawin Dapper. [https://gaw.in](https://gaw.in)
