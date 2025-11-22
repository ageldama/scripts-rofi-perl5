# scripts-rofi-perl5
Script Launcher + Rofi

1. Launch script in directories (searched recursively)
1. alternatively, Launch scripts in `x-terminal-emulator`
1. Save launch history and List scripts in recent used order


# REQUIREMENTS

1. [Perl 5.40+](https://www.perl.org/)
1. [Rofi 1.7.5+](https://github.com/davatorium/rofi)


# SYNOPSIS

```shell
./scripts-rofi.pl -S $HOME/local/scripts:$HOME/.local/scripts -s -p -e
```


# OPTIONS

```shell
./scripts-rofi.pl --help

...
List content of SCRIPT_DIRS and ask to select:

  -p : print selection
  -s : save selection
  -e : execute selection
  -S SCRIPT_DIRS      : `:'-separated list
  -D HIST_DB_FILE
  -T XTERM_COMMAND
```


# COPYRIGHT & LICENSE

1. MIT License (See `LICENSE`)
1. Written by Jonghyouk Yun, 2025.
