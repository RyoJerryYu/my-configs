# concept

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


# vscode shortcut binding


| command                                                                      | key before              | key after                | why                           |
| ---------------------------------------------------------------------------- | ----------------------- | ------------------------ | ----------------------------- |
| Delete Line                                                                  | `ctrl + shift + k`      | -                        | For Focus Editor up           |
| Search: Replace in Files                                                     | `ctrl + shift + h`      | -                        | For Focus Editor Left         |
| View: Focus Left Editor Group `workbench.action.focusLeftGroup`              | `ctrl + K ctrl + Left`  | `ctrl + shift + h`       | For moving windows with hjkl. |
| View: Focus Right Editor Group `workbench.action.focusRightGroup`            | `ctrl + K ctrl + Right` | `ctrl + shift + l`       | For moving windows with hjkl. |
| View: Focus Editor Group Above `workbench.action.focusAboveGroup`            | `ctrl + K ctrl + Up`    | `ctrl + shift + k`       | For moving windows with hjkl. |
| View: Focus Editor Group Below `workbench.action.focusBelowGroup`            | `ctrl + K ctrl + Down`  | `ctrl + shift + j`       | For moving windows with hjkl. |
| View: Move Editor into Group Above `workbench.action.moveEditorToAboveGroup` | -                       | `ctrl + shift + alt + k` | For moving windows with hjkl. |
| View: Move Editor into Group Below `workbench.action.moveEditorToBelowGroup` | -                       | `ctrl + shift + alt + j` | For moving windows with hjkl. |
| View: Move Editor into Group Left `workbench.action.moveEditorToLeftGroup`   | -                       | `ctrl + shift + alt + h` | For moving windows with hjkl. |
| View: Move Editor into Group Right `workbench.action.moveEditorToRightGroup` | -                       | `ctrl + shift + alt + l` | For moving windows with hjkl. |

The json code for vscode shortcut binding is as `keybindings.json` below.

# vscodevim plugin config

The json code for settings is as `settings.json` below.
