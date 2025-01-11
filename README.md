
# Tmux configuration

## Notes

- This configuration is only designed to be used on a Linux machine.
- The audio controls only work for pulse audio, using the `pactl` program.

## Assumptions

- There is a script `get-ipv4.sh` that would output the current IPv4 address to stdout and is in your `$PATH`.
- There is a script `get-battery-percentage.sh` that would output the current battery percentage to stdout and is in your `$PATH`.
- Your tmux version is recent enough. Tested using tmux version `tmux 3.0a`.

## How to setup

- Rename the configuration file `./tmux-config` to `./.tmux.conf`
- Move `./.tmux.conf` to your home directory `$HOME/`
