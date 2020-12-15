 # Shortcuts to Improve Your Bash & Zsh Productivity

The zsh shell adopt in oh-my-zsh framework. So some key mapping might difference between native zsh shell.
```
e.g. CTRL + S, CTRL + Q for freeze/unfreeze output to the terminal
```

| Shortcuts          | Bash<br>(ver:5.0.17) | Zsh<br>(ver:5.8)<br> | Action                                                              |
| ------------------ | -------------------- | -------------------- | ------------------------------------------------------------------- |
| CTRL + A           | [O]                  | [O]                  | Move to the beginning of the line                                   |
| CTRL + E           | [O]                  | [O]                  | Move to the end of the line                                         |
| ALT + B            | [O]                  | [O]                  | Move one word backward          (Equal CTRL + left arrow)           |
| ALT + F            | [O]                  | [O]                  | Move one word forward           (Equal CTRL + right arrow)          |
| CTRL + B           | [O]                  | [O]                  | Move one character backward     (Equal left arrow)                  |
| CTRL + F           | [O]                  | [O]                  | Move one word forward           (Equal right arrow)                 |
| CTRL + U           | [O]                  | [X]                  | Clear the characters on the line before the current cursor position |
| CTRL + U           | [X]                  | [O]                  | Clear the entire line                                               |
| CTRL + K           | [O]                  | [O]                  | Clear the characters on the line after the current cursor position  |
| CTRL + W           | [O]                  | [O]                  | Delete the word in front of the cursor                              |
| ALT + D            | [O]                  | [O]                  | Delete the word after the cursor                                    |
| CTRL + R           | [O] reverse-i-search | [O] bck-i-search     | Search history                                                      |
| CTRL + Shift + R   | [O]                  | [O]                  | Search history                  (Reverse Show Expression)           |
| CTRL + G           | [O]                  | [O]                  | Escape from search mode                                             |
| CTRL + _           | [O]                  | [O]                  | Undo the last change                                                |
| CTRL + L           | [O]                  | [O]                  | Clear screen                                                        |
| CTRL + S           | [O]                  | [X]                  | Stop output to screen                                               |
| CTRL + S           | [X]                  | [O] fwd-i-search     | Search history                                                      |
| CTRL + Q           | [O]                  | [X]                  | Re-enable screen output                                             |
| CTRL + C           | [O]                  | [O]                  | Terminate/kill current foreground process                           |
| CTRL + Z           | [O]                  | [O]                  | Suspend/stop current foreground process                             |
| CTRL + J           | [O]                  | [O]                  | Equal Enter key                                                     |
| CTRL + M           | [O]                  | [O]                  | Equal Enter key                                                     |
| CTRL + H           | [O]                  | [O]                  | Delete the character before the cursor  (Equal Backspace key)       |
| CTRL + D           | [O]                  | [O]                  | Delete the character after the cursor   (Equal Backspace key)       |
| CTRL + X CTRL + E  | [O]                  | [O]                  | Readline's edit-and-execute-command                                 |
| CTRL + V ^M        | [O]                  | [O]                  | To show control character ^M(you can type other control character)  |
| CTRL + N           | [O]                  | [O]                  | Find Next Expression        (Equal Down arrow)                      |
| CTRL + P           | [O]                  | [O]                  | Find Previous Expression    (Equal Up arrow)                        |
| CTRL + I           | [O]                  | [O]                  | Equal Tab key                                                       |
| ALT + C            | [O]                  | [O]                  | Initial-capitalize a word                                           |
| CTRL + T           | [O]                  | [O]                  | Switch the character after cursor                                   |
| ALT + T            | [O]                  | [O]                  | Switch the character after cursor                                   |
| ESC + T            | [O]                  | [O]                  | Switch the word after cursor                                        |
| ALT+ U             | [O]                  | [O]                  | Capitalize all characters in a word after the cursor.               |
| ALT + .            | [O]                  | [O]                  | use the last word of the previous command  (Loop through)           |
| CTRL + X  CTRL + X | [O]                  | [O]                  | Move between start of command line and current cursor position      |
| CTRL + Y           | [O]                  | [O]                  | Retrieves last item that you deleted or cut.                        |
| CTRL + [           | [O]                  | [O]                  | Equal Esc key                                                       |
| ALT + Y            | [O]                  | [O]                  | Paste previously cut text.(use it after CTRL + Y)  (Loop through)   |
| CTRL + O           | [O]                  | [X]                  | Execute present command and display previous command.               |
|                    |                      |                      |                                                                     |
|                    |                      |                      | Miscellaneous                                                       |
|                    |                      |                      | ALT + .  ==  Alt - _                                                |
|                    |                      |                      | CTRL + W == ESC + Backspace == ALT + Backspace                      |
|                    |                      |                      | CTRL + right arrow == ALT + right arrow == ESC and then B           |
|                    |                      |                      | CTRL + left arrow == ALT + left arrow == ESC and then F             |
|                    |                      |                      | CTRL - _  ==  CTRL - x CTRL - U                                     |
|                    |                      |                      |                                                                     |
|                    |                      |                      | Transpose Text or Change Case on the Command Line                   |
|                    | [O]                  | [O]                  |                                                                     |

| Command | Bash<br>(ver:5.0.17) | Zsh<br>(ver:5.8)<br> | Action                                                     |
| ------- | -------------------- | -------------------- | ---------------------------------------------------------- |
| !!      | [O]                  | [O]                  | Execute last command in history                            |
| !ls     | [O]                  | [O]                  | Execute last command in history beginning with abc         |
| !ls:p   | [O]                  | [O]                  | Print last command in history beginning with abc           |
| !$      | [O]                  | [O]                  | Use the last word of the previous command (same as Alt +.) |
| !\$:p   | [O]                  | [O]                  | Displays the word that !\$ would execute.                  |
| !*      | [O]                  | [O]                  | Displays the last word of the previous command.            |
| !\*:p   | [O]                  | [O]                  | Displays the last word that !\* would substitute.          |

In history search, you can use press ctrl+r(bash) ctrl+r/ctrl+s(oh-my-zsh) until you find the entry you're looking for.<p>
Press `Enter` to execute the current expression.<p>
Press `Right arrow` to modify the current expression.<p>
Press `Esc` to select the current expression.<p>
Press `Ctrl + g` to escape from search mode.

Use `set -o` to show all mode.

### Repeat motion:
`MetaKey` + `Count`  Command
> MetaKey: Default Meta Key是`Alt` or `Esc`.<br>
> Count: Repeat times,get reverse if count < 0<br>
> Command: May be characters/control characters.
>>(Should be spread between Count and Command via CTRL+V if characters is number)<br>
>e.g.<br>
>`MetaKey` + `12` -> a get 12 a<br>
>`MetaKey` + `3` ALT + B -> cursor move left 3 words<br>
>`MetaKey` + `-3` ALT + B -> cursor move right 3 words<br>
>`MetaKey` + `13` CTRL + V 0 -> get 13 0<br>


source :<br>
[ The Best Keyboard Shortcuts for Bash (aka the Linux and macOS Terminal) ](https://www.howtogeek.com/howto/ubuntu/keyboard-shortcuts-for-bash-command-shell-for-ubuntu-debian-suse-redhat-linux-etc/)<br>
[ Shortcuts to improve your bash & zsh productivity ](http://www.geekmind.net/2011/01/shortcuts-to-improve-your-bash-zsh.html)<br>
[ Using keyboard-shortcuts with zsh ](https://dev.to/ecologic/using-keyboard-shortcuts-with-zsh-16b)<br>
[ Bash Shell 快速鍵 (emacs-style) ](https://blog.codylab.com/bash-shell-shortcut/)<br>
[ The List Of Useful Bash Keyboard Shortcuts ](https://ostechnix.com/list-useful-bash-keyboard-shortcuts/)<br>
[ Bash Shell 快速鍵 ](https://blog.longwin.com.tw/2006/09/bash_hot_key_2006/)<br>
[ Useful Linux Command Line Bash Shortcuts You Should Know ](https://www.tecmint.com/linux-command-line-bash-shortcut-keys/)<br>
[ Shortcuts to move faster in Bash command line ](http://teohm.com/blog/shortcuts-to-move-faster-in-bash-command-line/)<br>
[ shell 终端使用技巧 ](https://ahuigo.github.io/b/c/shell-zsh#/)<br>