## Terminal setup

1. tmux
2. vim
  - theme: iceberg (iceberg is not working well in windows system)
3. zsh
4. gitconfig

## VS Code vim shortcut binding

| vscode vim shortcut  | commands                                                    | Note                                                         | rate (1 ~ 5) |
| -------------------- | ----------------------------------------------------------- | ------------------------------------------------------------ | ------------ |
| `<leader-n>`         | `explorer.newFile`                                          | easy to create new file without clicking sidebar             | 2            |
| `gf` (normal mode)   | `editor.action.peekImplementation`                          | easy to check code implementation without using the mouse    | 5            |
| `gd` (normal mode)   | `editor.action.goToImplementation`                          | built-in binding in vscode-vim                               | 5            |
| `<leader><leader-c>` | `merge-conflict.accept.current`                             | easy to resolve conflict in keyboard (gitlens required)      | 4            |
| `<leader><leader-i>` | `merge-conflict.accept.incoming`                            | easy to resolve conflict in keyboard                         | 4            |
| `<leader><leader-b>` | `merge-conflict.accept.both`                                | easy to resolve conflict in keyboard                         | 4            |
| `<leader-s>`         | `workbench.action.quickOpenTerm`                            | useful when open **multiple** terminal window in vscode<br /> | 4            |
| `<leader-c>`         | `gitlens.copyRemoteFileUrlFrom`                             | I found it useful when you want to share the current file in local via GitHub URL | 5            |
| `<leader-b>`         | `gitlens.toggleFileBlame`                                   | Really easy to check blame with this shortcut                | 4            |
| `<leader-p>`         | `gitlens.openBlamePriorToChange`                            | Tracking git blame in vscode and vim is really amazing!      | 4            |
| `<leader-a>`         | `workbench.view.explorer`                                   | Focus explorer view, you can use hjkl to navigate the file tree!<br />press o to open file | 5            |
| `<leader><leader-r>` | `revealFileInOS`                                            | easy to check image, assets or something in folder view      | 1            |
| `ff`                 | `formatDocument`                                            |                                                              | 3            |
| `++`                 | `workbench.action.increaseViewSize`                         | useful when you split the editor group and want to adjust size | 3            |
| `--`                 | `workbench.action.decreaseViewSize`                         |                                                              | 3            |
| `\`                  | `workbench.action.editor.changeLanguageMode`                | easy to change language                                      | 2            |
| `<leader-q>`         | `workbench.action.quickOpenNavigateNextInRecentFilesPicker` |                                                              |              |


