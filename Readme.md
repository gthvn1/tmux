# Tmux

## Installation

- Just need to clone the repo in **${HOME}/.config/tmux**:
  - `git clone https://github.com/gthvn1/tmux.git ~/.config/tmux`
- *tmux.conf* is using [tpm plugin](https://github.com/tmux-plugins/tpm).
  You need to clone the plugin as well:
  - `git clone https://github.com/tmux-plugins/tpm ~/.tmux/plugins/tpm`
  - To update plugins in tmux, press prefix + I (capital i, as in Install) to fetch the plugin.
If **~/.config/tmux** is not read by your version of tmux you can start tmux like this:
  - `tmux -f ~/.config/tmux/tmux.conf`
Or you can copy **tmux.conf** to **~/.tmux.conf**
