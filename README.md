# tmux.conf
```
cd ~/code
git clone https://github.com/jayache80/tmuxconf.git
cd ~
ln -s code/tmuxconf/.tmux.conf .tmux.conf
```
For vim colors and line numbers to show up ok, you have to do
```
alias tmux="tmux -2"
```
in your `.bash_profile`

## Plugins
First install the tmux plugin manager, so you can easily install other plugins.
```
git clone https://github.com/tmux-plugins/tpm ~/.tmux/plugins/tpm
```
This `.tmux.conf` expects you to have installed `tpm`. Running `prefix + I` the
first time you set up tmux will automatically fetch and install remaining
plugins that would be included in this .tmux.conf.
