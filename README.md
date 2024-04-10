# dlew's scripts!
make sure to add this folder to your `PATH`!

## tmux-sessionzer
shamlessly stolen from [ThePrimeagen](https://github.com/ThePrimeagen/.dotfiles/blob/master/bin/.local/scripts/tmux-sessionizer)!

will search the directories (`~/dlew/public` & `~/dlew/private`) for child directories with `1` depth

all found directories will then be displayed and sent to `fzf` where you can then select and fuzzy find your desired session!

if a session already exists for that directory (and name) then a new session will not be created, but instead switched to

### requires
- `fzf`
- `tmux`
