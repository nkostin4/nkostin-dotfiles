# N. Kostin's dotfiles

This repo, which I forked from [Luke Smith](https://lukesmith.xyz), contains my dotfiles, which I use on an installation of [Artix Linux](https://artixlinux.org).

- Useful scripts are in `~/.local/bin/`
- Settings for:
	- neovim (text editor)
	- zsh (shell)
	- lf (file manager)
	- mpd/ncmpcpp (music)
	- sxiv (image/gif viewer)
	- mpv (video player)
	- other stuff like xdg default programs, inputrc and more, etc.
- I try to minimize what's directly in `~` so:
	- All configs that can be in `~/.config/` are.
	- Some environmental variables have been set in `~/.zprofile` to move configs into `~/.config/`
- Bookmarks in text files used by various scripts (like `~/.local/bin/shortcuts`)
	- File bookmarks in `~/.config/shell/bm-files`
	- Directory bookmarks in `~/.config/shell/bm-dirs`

## Usage

These dotfiles are intended to go with numerous suckless programs I use:

- [dwm](https://github.com/nkostin4/dwm) (window manager)
- [slstatus](https://github.com/nkostin4/slstatus) (statusbar)
- [st](https://github.com/lukesmithxyz/st) (terminal emulator)

I also recommend trying out
[mutt-wizard](https://github.com/lukesmithxyz/mutt-wizard), which additionally
works with this setup. It gives you an easy-to-install terminal-based email
client regardless of your email provider. It is integrated into these dotfiles
as well.

## Install these dotfiles and all dependencies

Use [the following](https://github.com/nkostin4/nkostin-deploy-artix) to autoinstall everything:

```
curl -LO https://raw.githubusercontent.com/nkostin4/nkostin-deploy-artix/master/deploy.sh
sh deploy.sh
```

or clone the repo files directly to your home directory and install the
[dependencies](https://github.com/nkostin4/nkostin-deploy-artix/blob/master/progs.csv).
