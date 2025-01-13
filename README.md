
# Tmux configuration

## Notes

- This configuration is only designed to be used on a Linux machine.

## Assumptions

- There is a script `get-ipv4.sh` that would output the current IPv4 address to stdout. In your `$PATH` and executable.
- There is a script `get-battery-percentage.sh` that would output the current battery percentage to stdout. In your `$PATH and executable`.
- There is a script `volume-increase.sh` that would increase the audio volume. In your `$PATH and executable`.
- There is a script `volume-decrease.sh` that would decrease the audio volume. In your `$PATH and executable`.
- There is a script `volume-toggle-mute.sh` that would toggle the audio mute. In your `$PATH and executable`.
- Your tmux version is recent enough. Tested using tmux version `tmux 3.0a`.

## How to setup

- Rename the configuration file `./tmux-config` to `./.tmux.conf`
- Move `./.tmux.conf` to your home directory `$HOME/`
