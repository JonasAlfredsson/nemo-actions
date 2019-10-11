# nemo-actions

This is a small collection of "Nemo actions", which are basically small
executable scripts that are visible as options in the right-click menu of the
[Nemo][3] file browser.

Nemo is the default file browser of the Cinnamon desktop environment, which is
the default in Linux Mint.



# Installation

"Installing" these scripts is done by placing them in one of the following
folders:

- `~/.local/share/nemo/actions/`
    - Placing them here will make them available only for the current user.
- `/usr/share/nemo/actions/`
    - Placing them here will make them avilable for everyone on the system.

A quick git `clone` command can look like this:

```bash
git clone git@github.com:JonasAlfredsson/nemo-actions.git ~/.local/share/nemo/actions/
```



# Usage

A detailed example of a [Nemo action file][1] can be found in the official
repository, and as usual the [ArchWiki][2] provides additional useful
information to the subject at hand. So I suggest you check that out both of
these if you want to create your own custom actions. The only thing to remember
is that all files need to have `.nemo_action` as their file ending, otherwise
they will not be recognized by the file browser.



[1]: https://github.com/linuxmint/nemo/blob/master/files/usr/share/nemo/actions/sample.nemo_action
[2]: https://wiki.archlinux.org/index.php/Nemo
[3]: https://github.com/linuxmint/nemo
