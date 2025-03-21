# tmux

My personal tmux config file. Use as

 $ cp tmux.conf ${HOME}/.tmux.conf

# changes from default behavior

Changed the prefix to Ctrl-t (t from tmux). This works nice with my nviim settings

Never let tmux touch my ESC key

Requires powerline, see [this install reference](https://www.baeldung.com/linux/powerline-installation-configuration)

Better split commands;

 Ctrl-t | = Vertical split

 Ctrl-t - = horizontal split

Moving through windows with Alt-Arrow keys (works nicely with my nvim settings)

Mouse support is default on

No auto-rename titles (use the Ctrl-, combination)

Borders are colored
