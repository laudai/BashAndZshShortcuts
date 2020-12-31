 # Shortcuts to Improve Your Bash & Zsh Productivity

The zsh shell adopt in oh-my-zsh framework. So some key mapping might difference between native zsh shell.
```
e.g. CTRL + S, CTRL + Q for freeze/unfreeze output to the terminal
```

| Shortcuts          | Bash<br>(ver:5.0.17)    | Zsh<br>(ver:5.8)    | Action                                                                         |
| ------------------ | ----------------------- | ------------------- | ------------------------------------------------------------------------------ |
| Cursor Moving      |
| CTRL + B           | [O]                     | [O]                 | Move one character backward    (Equal left arrow)                              |
| CTRL + F           | [O]                     | [O]                 | Move one character forward     (Equal right arrow)                             |
| ALT + B            | [O]                     | [O]                 | Move one word backward         (Equal CTRL + left arrow)                       |
| ALT + F            | [O]                     | [O]                 | Move one word forward          (Equal CTRL + right arrow)                      |
| CTRL + A           | [O]                     | [O]                 | Move to the beginning of the line                                              |
| CTRL + E           | [O]                     | [O]                 | Move to the end of the line                                                    |
| CTRL + X CTRL + X  | [O]                     | [O]                 | Move between start of command line and current cursor position                 |
| ^ + \] + char      | [O]                     | [X]                 | Moves the cursor backward to the previous occurance of char                    |
| ^ + ALT + ] + char | [O]                     | [X]                 | Moves the cursor forward to the next occurance of char                         |
| Delete and Paste   |
| CTRL + H           | [O]                     | [O]                 | Delete the character before the cursor  (Equal Backspace key)                  |
| CTRL + D           | [O]                     | [O]                 | Delete the character after the cursor   (Equal Delete key)                     |
| CTRL + W           | [O]                     | [O]                 | Delete the word before the cursor                                              |
| ALT + D            | [O]                     | [O]                 | Delete the word after the cursor                                               |
| CTRL + U           | [O]                     | [X]                 | Delete the characters on the line before the current cursor position           |
| CTRL + U           | [X]                     | [O]                 | Delete the entire line                                                         |
| CTRL + K           | [O]                     | [O]                 | Delete the characters on the line after the current cursor position            |
| CTRL + Y           | [O]                     | [O]                 | Retrieves last item that you deleted or cut                (Exclude ^H, ^D)    |
| ALT + Y            | [O]                     | [O]                 | Paste previously cut text             (Use it after CTRL + Y, Loop through)    |
| Undo               |
| CTRL + /           | [O]                     | [O]                 | Undo the last change                                                           |
| CTRL + _           | [O]                     | [O]                 | Undo the last change                                                           |
| History            |
| CTRL + R           | [O]<br>reverse-i-search | [O]<br>bck-i-search | Search history                                                                 |
| CTRL + Shift + R   | [O]                     | [O]                 | Search history     (Reverse Select Command)                                    |
| CTRL + S           | [X]                     | [O]<br>fwd-i-search | Search history                                                                 |
| CTRL + G           | [O]                     | [O]                 | Escape from history search mode                                                |
| CTRL + N           | [O]                     | [O]                 | Go to next command in the command history      (Equal Down arrow,Loop through) |
| CTRL + P           | [O]                     | [O]                 | Go to previous command in the command history    (Equal Up arrow,Loop through) |
| ALT + <            | [O]                     | [O]                 | Move to the first line in the history                                          |
| ALT + >            | [O]                     | [O]                 | Move to the end of the input history                                           |
|                    |                         |                     | export HISTSIZE = 0        //Disable history                                   |
|                    |                         |                     | history -c                 //Clear history                                     |
| Screen             |
| CTRL + L           | [O]                     | [O]                 | Clear screen                                                                   |
| CTRL + S           | [O]                     | [X]                 | Stop output to screen                                                          |
| CTRL + Q           | [O]                     | [X]                 | Re-enable screen output                                                        |
| Process            |
| CTRL + C           | [O]                     | [O]                 | Terminate/kill current foreground process                                      |
| CTRL + Z           | [O]                     | [O]                 | Suspend/stop current foreground process                                        |
|                    |                         |                     | Transpose Text or Change Case in the Command Line                              |
| CTRL + T           | [O]                     | [O]                 | Switch the character before cursor                                             |
| ALT + T            | [O]                     | [O]                 | Switch the word after cursor                                                   |
| ESC + T            | [O]                     | [O]                 | Switch the word after cursor                                                   |
| ALT + C            | [O]                     | [O]                 | Initial-capitalize a word                           (Loop through)             |
| ALT + U            | [O]                     | [O]                 | Uppercase all characters in a word after the cursor.(Loop through)             |
| ALT + L            | [O]                     | [X]                 | Lowercase all characters in a word after the cursor.(Loop through)             |
| Miscellaneous      |
| CTRL + X CTRL + E  | [O]                     | [O]                 | Readline's edit-and-execute-command                                            |
| CTRL + V ^M        | [O]                     | [O]                 | To show control character ^M (you can type other control character)            |
| ALT + .            | [O]                     | [O]                 | Use the last word of the previous command            (Loop through)            |
| CTRL + O           | [O]                     | [X]                 | Execute present command and display previous command                           |
| Equal Control key  |
| CTRL + I           | [O]                     | [O]                 | Equal Tab key                                                                  |
| CTRL + J           | [O]                     | [O]                 | Equal Enter key(line feed)                                                     |
| CTRL + M           | [O]                     | [O]                 | Equal Enter key                                                                |
| CTRL + [           | [O]                     | [O]                 | Equal Esc key                                                                  |
|                    |                         |                     | ALT + .  ==  Alt - _                                                           |
|                    |                         |                     | CTRL + W == ESC + Backspace == ALT + Backspace                                 |
|                    |                         |                     | CTRL + Right arrow == ALT + Right arrow == ESC and then B                      |
|                    |                         |                     | CTRL + Left arrow == ALT + Left arrow == ESC and then F                        |
|                    |                         |                     | CTRL - _  ==  CTRL - X CTRL - U                                                |

| Command | Bash<br>(ver:5.0.17) | Zsh<br>(ver:5.8)<br> | Action                                            |
| ------- | -------------------- | -------------------- | ------------------------------------------------- |
| !!      | [O]                  | [O]                  | Execute last command in history                   |
| !ls     | [O]                  | [O]                  | Execute last command in history beginning with ls |
| !ls:p   | [O]                  | [O]                  | Print last command in history beginning with ls   |
| !$      | [O]                  | [O]                  | Last argument of last command (same as Alt +.)    |
| !^      | [O]                  | [O]                  | First argument of last command                    |
| !\$:p   | [O]                  | [O]                  | Displays the word that !\$ would execute          |
| !*      | [O]                  | [O]                  | Displays the last word of the previous command    |
| !\*:p   | [O]                  | [O]                  | Displays the last word that !\* would substitute  |
---
### In history search
You can press CTRL + R(bash) CTRL + R/CTRL + S(oh-my-zsh) until you find the entry you're looking for.<p>
Press `Enter` to execute the current expression.<p>
Press `Right arrow` to modify the current expression.<p>
Press `Esc` to select the current expression.<p>
Press `CTRL + G` to escape from search mode.<p>

### Repeat motion:
`MetaKey` + `Count`  Command
> MetaKey : Default Meta Key is `Alt` or `Esc`.<br>
> Count : Repeat times,get reverse if count < 0<br>
> Command : Can be characters/control characters.<br>
> **Should be spread between Count and Command via CTRL+V if characters is number**<br>
>e.g.<br>
>`MetaKey` + `12` a -> get 12 a<br>
>`MetaKey` + `3` ALT + B -> cursor move left 3 words<br>
>`MetaKey` + `-3` ALT + B -> cursor move right 3 words<br>
>`MetaKey` + `13` CTRL + V 0 -> get 13 0<br>

### Others :
Use `set -o` to show all mode.<br>
[ Zsh Line Editor ](http://zsh.sourceforge.net/Doc/Release/Zsh-Line-Editor.html#Movement) **[ highly recommended ]**<br>

source :<br>
[ shell 终端使用技巧 ](https://ahuigo.github.io/b/c/shell-zsh#/) **[ highly recommended ]**<br>
[ How-to: Bash Keyboard Shortcuts ](https://ss64.com/bash/syntax-keyboard.html) **[ highly recommended ]**<br>
[ Bash Shell 快速鍵 (emacs-style) ](https://blog.codylab.com/bash-shell-shortcut/)<br>
[ Bash Shell 快速鍵 ](https://blog.longwin.com.tw/2006/09/bash_hot_key_2006/)<br>
[ The Best Keyboard Shortcuts for Bash (aka the Linux and macOS Terminal) ](https://www.howtogeek.com/howto/ubuntu/keyboard-shortcuts-for-bash-command-shell-for-ubuntu-debian-suse-redhat-linux-etc/)<br>
[ Shortcuts to move faster in Bash command line ](http://teohm.com/blog/shortcuts-to-move-faster-in-bash-command-line/)<br>
[ Shortcuts to improve your bash & zsh productivity ](http://www.geekmind.net/2011/01/shortcuts-to-improve-your-bash-zsh.html)<br>
[ The List Of Useful Bash Keyboard Shortcuts ](https://ostechnix.com/list-useful-bash-keyboard-shortcuts/)<br>
[ Using keyboard-shortcuts with zsh ](https://dev.to/ecologic/using-keyboard-shortcuts-with-zsh-16b)<br>
[ Useful Linux Command Line Bash Shortcuts You Should Know ](https://www.tecmint.com/linux-command-line-bash-shortcut-keys/)<br>

## License

BashAndZshShortcuts is released under the [MIT license](LICENSE.txt).