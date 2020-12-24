 # 增進你Bash、Zsh生產效率的快速鍵

在此整理表格中，我zsh是採用 oh-my-zsh框架，目前有部份的快捷鍵會與原生zsh有所不同
```
e.g. CTRL + S, CTRL + Q 凍結/解凍顯示畫面輸出
```

| 快捷鍵             | Bash<br>(ver:5.0.17)    | Zsh<br>(ver:5.8)    | 動作說明                                                             |
| ------------------ | ----------------------- | ------------------- | -------------------------------------------------------------------- |
| 游標移動           |
| CTRL + B           | [O]                     | [O]                 | 游標向前移動一字元       (等同於左鍵)                                |
| CTRL + F           | [O]                     | [O]                 | 游標向後移動一字元       (等同於右鍵)                                |
| ALT + B            | [O]                     | [O]                 | 游標向前移動一單字       (等同於 CTRL + 左鍵)                        |
| ALT + F            | [O]                     | [O]                 | 游標向後移動一單字       (等同於 CTRL + 右鍵)                        |
| CTRL + A           | [O]                     | [O]                 | 游標移動到行首                                                       |
| CTRL + E           | [O]                     | [O]                 | 游標移動到行末                                                       |
| CTRL + X CTRL + X  | [O]                     | [O]                 | 游標從現在位置到行首之間移動                                         |
| ^ + \] + char      | [O]                     | [X]                 | 游標向後移動到char字元                                               |
| ^ + ALT + ] + char | [O]                     | [X]                 | 游標向前移動到char字元                                               |
| 刪除與貼上         |
| CTRL + H           | [O]                     | [O]                 | 向前刪除一字元           (等同於 Backspace)                          |
| CTRL + D           | [O]                     | [O]                 | 向後刪除一字元           (等同於 Delete)                             |
| CTRL + W           | [O]                     | [O]                 | 向前刪除一單字                                                       |
| ALT + D            | [O]                     | [O]                 | 向後刪除一單字                                                       |
| CTRL + U           | [O]                     | [X]                 | 從現在游標位置刪除至行首                                             |
| CTRL + U           | [X]                     | [O]                 | 整行刪除                                                             |
| CTRL + K           | [O]                     | [O]                 | 從現在游標位置刪除至行末                                             |
| CTRL + Y           | [O]                     | [O]                 | 取回你最後刪除的單字               (不包括使用 ^H, ^D)               |
| ALT + Y            | [O]                     | [O]                 | 貼上最後你刪除的單字            (須在 CTRL + Y 之後使用, 可循環操作) |
| 重作               |
| CTRL + /           | [O]                     | [O]                 | 回到上一步驟                                                         |
| CTRL + _           | [O]                     | [O]                 | 回到上一步驟                                                         |
| 歷史紀錄           |
| CTRL + R           | [O]<br>reverse-i-search | [O]<br>bck-i-search | 搜尋歷史紀錄                                                         |
| CTRL + Shift + R   | [O]                     | [O]                 | 搜尋歷史紀錄     (反向選取紀錄)                                      |
| CTRL + S           | [X]                     | [O]<br>fwd-i-search | 搜尋歷史紀錄                                                         |
| CTRL + G           | [O]                     | [O]                 | 離開搜尋歷史紀錄模式                                                 |
| CTRL + N           | [O]                     | [O]                 | 取得在歷史紀錄中的下一個命令         (等同於下鍵,可循環操作)         |
| CTRL + P           | [O]                     | [O]                 | 取得在歷史紀錄中的上一個命令         (等同於上鍵,可循環操作)         |
| ALT + <            | [O]                     | [O]                 | 移動到歷史紀錄中的第一個命令                                         |
| ALT + >            | [O]                     | [O]                 | 移動到歷史紀錄中的最後一個命令                                       |
|                    |                         |                     | export HISTSIZE = 0        //Disable history                         |
|                    |                         |                     | history -c                 //Clear history                           |
| 螢幕顯示           |
| CTRL + L           | [O]                     | [O]                 | 清除螢幕資料                                                         |
| CTRL + S           | [O]                     | [X]                 | 停止輸出至螢幕                                                       |
| CTRL + Q           | [O]                     | [X]                 | 重新輸出至螢幕                                                       |
| 程序               |
| CTRL + C           | [O]                     | [O]                 | 中止目前運行程序                                                     |
| CTRL + Z           | [O]                     | [O]                 | 暫停目前運行程序                                                     |
|                    |                         |                     | 在命列列中改變位置或改變大小寫                                       |
| CTRL + T           | [O]                     | [O]                 | 與游標前一字元交換                                                   |
| ALT + T            | [O]                     | [O]                 | 與游標後一單字交換                                                   |
| ESC + T            | [O]                     | [O]                 | 與游標後一單字交換                                                   |
| ALT + C            | [O]                     | [O]                 | 將該單字轉換成首字大寫                 (可循環操作)                  |
| ALT + U            | [O]                     | [O]                 | 將游標後的單字全部字元轉換成大寫         (可循環操作)                |
| ALT + L            | [O]                     | [X]                 | 將游標後的單字全部字元轉換成小寫         (可循環操作)                |
| 雜項               |
| CTRL + X CTRL + E  | [O]                     | [O]                 | 透過編輯器編輯目前命令列                                             |
| CTRL + V ^M        | [O]                     | [O]                 | 顯示控制字元 ^M (你可以使用其他控制字元)                             |
| ALT + .            | [O]                     | [O]                 | 取得上一個命令的最後一個參數                (可循環操作)             |
| CTRL + O           | [O]                     | [X]                 | 執行現在命令後，顯示上一次的命令                                     |
| 相等的控制鍵       |
| CTRL + I           | [O]                     | [O]                 | 等同於 Tab 鍵                                                        |
| CTRL + J           | [O]                     | [O]                 | 等同於 Enter 鍵(line feed)                                           |
| CTRL + M           | [O]                     | [O]                 | 等同於 Enter 鍵                                                      |
| CTRL + [           | [O]                     | [O]                 | 等同於 Esc 鍵                                                        |
|                    |                         |                     | ALT + .  ==  Alt - _                                                 |
|                    |                         |                     | CTRL + W == ESC + Backspace == ALT + Backspace                       |
|                    |                         |                     | CTRL + 右鍵 == ALT + 右鍵 == 按 ESC 後 再按 B                        |
|                    |                         |                     | CTRL + 左鍵 == ALT + 左鍵 == 按 ESC 後 再按 F                        |
|                    |                         |                     | CTRL - _  ==  CTRL - X CTRL - U                                      |

| 指令  | Bash<br>(ver:5.0.17) | Zsh<br>(ver:5.8)<br> | 指令說明                                   |
| ----- | -------------------- | -------------------- | ------------------------------------------ |
| !!    | [O]                  | [O]                  | 執行歷史紀錄中，最後一個命令               |
| !ls   | [O]                  | [O]                  | 執行歷史紀錄中，最後一個ls開頭的命令       |
| !ls:p | [O]                  | [O]                  | 顯示歷史紀錄中，最後一個ls開頭的命令       |
| !$    | [O]                  | [O]                  | 取得上一個命令的最後一個參數 (同等 Alt +.) |
| !^    | [O]                  | [O]                  | 取得上一個命令的第一個參數                 |
| !\$:p | [O]                  | [O]                  | 顯示上一個命令的最後一個參數               |
| !*    | [O]                  | [O]                  | 取得上一個命令的所有參數                   |
| !\*:p | [O]                  | [O]                  | 顯示上一個命令的所有參數                   |
---
### 歷史搜尋模式的操作方式
你可以透過 CTRL + R(bash) CTRL + R/CTRL + S(oh-my-zsh) 來找你想要的歷史命令
找到後，你可以透過
按下 `Enter` 執行現在所選的命令<p>
按下 `右鍵` 選擇並向右移動一字元<p>
按下 `Esc` 選擇該命令<p>
按下 `CTRL + G` 離開歷史搜尋模式<p>

### 重複動作:
`MetaKey` + `Count`  動作指令
> MetaKey : Meta Key 預設是 `Alt` 或 `Esc`<br>
> Count : 重複次數，如果count<0，則會朝向反向動作<br>
> Command : 可以是普通字元或控制字元<br>
> **如果在Command中，要印出數字字元，需要在數字字元前面加上CTRL + V動作**<br>
>e.g.<br>
>`MetaKey` + `12` a -> 得到12個a<br>
>`MetaKey` + `3` ALT + B -> 游標向前移動三個單字<br>
>`MetaKey` + `-3` ALT + B -> 游標向後移動三個單字<br>
>`MetaKey` + `13` CTRL + V 0 -> 得到13個0<br>

### Others :
透過 `set -o` 顯示所有模式<br>
[ Zsh Line Editor ](http://zsh.sourceforge.net/Doc/Release/Zsh-Line-Editor.html#Movement) **[  強烈推薦 ]**<br>

source :<br>
[ shell 终端使用技巧 ](https://ahuigo.github.io/b/c/shell-zsh#/) **[  強烈推薦 ]**<br>
[ How-to: Bash Keyboard Shortcuts ](https://ss64.com/bash/syntax-keyboard.html) **[  強烈推薦 ]**<br>
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