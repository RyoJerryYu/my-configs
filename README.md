# My Config

The repo that I am using to store my config files.

Moved from my gists.

# `vscode_keybindings`

My VSCode Setting File For Vim Mode in VSCode.


1. editor moving and splitting
    1. focus around `ctrl + shift + hjkl` (and change `ctrl` to `command` in MacOS)
    2. move editor around `ctrl + shift + alt + hjkl` (and change `ctrl` to `command` in MacOS)
2. quick moving and slow moving
    1. quick: `shift + jk` = `10j` `10k` , `shift + hl` = `^` `$`
    2. slow: `ctrl + jk` = `gj` `gk` , `ctrl + hl` = `g^` `g$` (used for one long line displayed as multiple line, usually in markdown)
3. tabbing: `tab` `shift + tab` = `>>` `<<`
4. goTos: `ga` = `editor.action.goToImplementation` (useful with the default `gd` `gh` command)
5. VSCode original keymapping: `ctrl+w` , `ctrl+t` , `ctrl+s` , `ctrl+z` , ` ctrl + shift + f`
6. When focusing VSCode explorer, new file and new folder command: `ctrl+n` , `ctrl+shift+n`


# `python_google_style`

My config files under ~/.config/ for Python that exactly match yapf styles for Google open source projects.

You could modify these files, or use it in your project instead of use it globally.

### Some addition

- Configuring yapf with VSCode settings.json is as same as specify it on the command line.
- The `pylintrc` file is exactly the same file as [pylintrc on google style guide](https://google.github.io/styleguide/pylintrc).
- For more project specification and team cooperation, you would be better to use config files in your project, instead of 
  global config under `~/.config/`
- You could use these files with [my VSCode setting file for Python](https://gist.github.com/RyoJerryYu/abab633f9aa876fb6947dfca869695d3) for whole automatic Google open source project experience in Python.

# `git_alias`

Some useful git alias I am using. Used to be https://gist.github.com/RyoJerryYu/e71b66fe725fd84adf491688f5de62fa .

# `vscode_setting_python`

Some vscode setting for python.

https://gist.github.com/RyoJerryYu/abab633f9aa876fb6947dfca869695d3
