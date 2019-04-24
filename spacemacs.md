# spacemacs

<!-- markdown-toc start - Don't edit this section. Run M-x markdown-toc-refresh-toc -->
**Table of Contents**

- [spacemacs](#spacemacs)
    - [Key bindings](#key-bindings)
        - [Lowercase letters](#lowercase-letters)
        - [Uppercase letters](#uppercase-letters)
        - [Numbers](#numbers)
        - [Punctuation](#punctuation)

<!-- markdown-toc end -->
## Key bindings (normal state)

### Lowercase letters

| Key     | Mnemonic     | Description                                                     | Function                   |
| :-----: | ------------ | --------------------------------------------------------------- | -------------------------- |
| **`a`** | *append*     | Switch to Insert state just after point.                        | `evil-append`              |
| **`b`** | *backward*   | Move the cursor to the beginning of the COUNT-th previous word. | `evil-backward-word-begin` |
| **`c`** | *change*     | Change text from BEG to END with TYPE.                          | `evil-change`              |
| **`d`** | *delete*     | Delete text from BEG to END with TYPE.                          | `evil-delete`              |
| **`e`** | *end*        | Move the cursor to the end of the COUNT-th next word.           | `evil-forward-word-end`    |
| **`f`** | *find*       | Move to the next COUNT-th occurrence of CHAR.                   | `evil-find-char`           |
| **`g`** | *goto*       | (prefix)                                                        |                            |
| **`h`** | *LEFT*       | Move cursor to the left by COUNT characters.                    | `evil-backward-char`       |
| **`i`** | *insert*     | Switch to Insert state just before point.                       | `evil-insert`              |
| **`j`** | *DOWN*       | Move the cursor COUNT lines down.                               | `evil-next-line`           |
| **`k`** | *UP*         | Move the cursor COUNT lines up.                                 | `evil-previous-line`       |
| **`l`** | *RIGHT*      | Move cursor to the right by COUNT characters.                   | `evil-forward-char`        |
| **`m`** | *mark*       | Set the marker denoted by CHAR to position POS.                 | `evil-set-marker`          |
| **`n`** | *next*       | Goes to the next occurrence.                                    | `evil-ex-search-next`      |
| **`o`** | *open*       | Insert a new line below point and switch to Insert state.       | `evil-open-below`          |
| **`p`** | *paste*      | Disable paste transient state if there is more than 1 cursor.   | `evil-mc-paste-after`      |
| **`q`** |              | Record a keyboard macro into REGISTER.                          | `evil-record-macro`        |
| **`r`** | *replace*    | Replace text from BEG to END with CHAR.                         | `evil-replace`             |
| **`s`** | *substitute* | Change a character.                                             | `evil-substitute`          |
| **`t`** | *to*         | Move before the next COUNT-th occurrence of CHAR.               | `evil-find-char-to`        |
| **`u`** | *undo*       | Undo changes.                                                   | `evil-tree-undo`           |
| **`v`** | *visual*     | Characterwise selection.                                        | `evil-visual-char`         |
| **`w`** | *word*       | Move the cursor to the beginning of the COUNT-th next word.     | `evil-forward-word-begin`  |
| **`x`** | *cross*      | Delete next character.                                          | `evil-delete-char`         |
| **`y`** | *yank*       | Saves the characters in motion into the kill-ring.              | `evil-yank`                |
| **`z`** | *scroll*     | (prefix)                                                        |                            |

### Uppercase letters

| Key     | Mnemonic     | Description                                                                                   | Function                         |
| :-----: | ------------ | --------------------------------------------------------------------------------------------- | -------------------------------- |
| **`A`** | *append*     | Switch to Insert state at the end of the current line.                                        | `evil-append-line`               |
| **`B`** | *back*       | Move the cursor to the beginning of the COUNT-th previous WORD.                               | `evil-backward-WORD-begin`       |
| **`C`** | *change*     | Change to end of line.                                                                        | `evil-change-line`               |
| **`D`** | *delete*     | Delete to end of line.                                                                        | `evil-delete-line`               |
| **`E`** | *end*        | Move the cursor to the end of the COUNT-th next WORD.                                         | `evil-forward-WORD-end`          |
| **`F`** | *find*       | Move to the previous COUNT-th occurrence of CHAR.                                             | `evil-find-char-backward`        |
| **`G`** | *goto*       | Go to the first non-blank character of line COUNT.                                            | `evil-goto-line`                 |
| **`H`** | *TOP*        | Move the cursor to line COUNT from the top of the window on the first non-blank character.    | `evil-window-top`                |
| **`I`** | *insert*     | Switch to insert state at beginning of current line.                                          | `evil-insert-line`               |
| **`J`** | *join*       | Join the selected lines.                                                                      | `evil-join`                      |
| **`K`** | *keyword*    | Look up the keyword at point.                                                                 | `evil-lookup`                    |
| **`L`** | *BOTTOM*     | Move the cursor to line COUNT from the bottom of the window on the first non-blank character. | `evil-window-bottom`             |
| **`M`** | *middle*     | Move the cursor to the middle line in the window on the first non-blank character.            | `evil-window-middle`             |
| **`N`** | *next*       | Goes the the previous occurrence.                                                             | `evil-ex-search-previous`        |
| **`O`** | *open*       | Insert a new line above point and switch to Insert state.                                     | `evil-open-above`                |
| **`P`** | *paste*      | Disable paste transient state if there is more than 1 cursor.                                 | `spacemacs/evil-mc-paste-before` |
| **`Q`** |              | (undefined)                                                                                   |                                  |
| **`R`** | *replace*    | Enable Replace state. Disable with negative ARG.                                              | `evil-replace-state`             |
| **`S`** | *substitute* | Change whole line.                                                                            | `evil-change-whole-line`         |
| **`T`** | *to*         | Move before the previous COUNT’th occurrence of CHAR.                                         | `evil-find-char-to-backward`     |
| **`U`** |              | (undefined)                                                                                   |                                  |
| **`V`** | *visual*     | Linewise selection.                                                                           | `evil-visual-line`               |
| **`W`** | *word*       | Move the cursor to the beginning of the COUNT-th next WORD.                                   | `evil-forward-WORD-begin`        |
| **`X`** | *cross*      | Delete previous character.                                                                    | `evil-delete-backward-char`      |
| **`Y`** | *yank*       | Saves whole lines into the kill-ring.                                                         | `evil-yank-line`                 |
| **`Z`** | *quit*       | (prefix)                                                                                      |                                  |

### Numbers

| Key     | Mnemonic | Description                                           | Function                                        |
| :-----: | -------- | ----------------------------------------------------- | ----------------------------------------------- |
| **`0`** | *bol*    | Move the cursor to the beginning of the current line. | `evil-digit-argument-or-evil-beginning-of-line` |
| **`1`** | *1*      | Part of the numeric argument for the next command.    | `digit-argument`                                |
| **`2`** | *2*      | Part of the numeric argument for the next command.    | `digit-argument`                                |
| **`3`** | *3*      | Part of the numeric argument for the next command.    | `digit-argument`                                |
| **`4`** | *4*      | Part of the numeric argument for the next command.    | `digit-argument`                                |
| **`5`** | *5*      | Part of the numeric argument for the next command.    | `digit-argument`                                |
| **`6`** | *6*      | Part of the numeric argument for the next command.    | `digit-argument`                                |
| **`7`** | *7*      | Part of the numeric argument for the next command.    | `digit-argument`                                |
| **`8`** | *8*      | Part of the numeric argument for the next command.    | `digit-argument`                                |
| **`9`** | *9*      | Part of the numeric argument for the next command.    | `digit-argument`                                |

### Punctuation

| Key        | Mnemonic             | Description                                                                                  | Function                             |
| :-------:  | -------------------  | -------------------------------------------------------------------------------------------- | ------------------------------------ |
| **`\``**   | *goto mark*          | Go to the marker specified by CHAR.                                                          | `evil-goto-mark`                     |
| **`~`**    | *invert case*        | Invert case of character.                                                                    | `evil-invert-char`                   |
| **`!`**    | *shell*              | Execute a shell command.                                                                     | `evil-shell-command`                 |
| **`@`**    | *macro*              | Execute keyboard macro MACRO, COUNT times.                                                   | `evil-execute-macro`                 |
| **`#`**    | *find previous*      | Go to the previous occurrence of symbol under point with `auto-highlight-symbol`             | `spacemacs/enter-ahs-backward`       |
| **`^`**    | *bol*                | Move the cursor to the first non-blank character of the current line.                        | `evil-first-non-blank`               |
| **`$`**    | *eol*                | Move the cursor to the end of the current line.                                              | `evil-end-of-line`                   |
| **`%`**    | *jump*               | Find the next item in this line after or under the cursor and jump to the corresponding one. | `evil-jump-item`                     |
| **`&`**    | *repeat substitute*  | Repeat last substitute command.                                                              | `evil-ex-repeat-substitute`          |
| **`*`**    | *find next*          | Go to the next occurrence of symbol under point with `auto-highlight-symbol`                 | `spacemacs/enter-ahs-forward`        |
| **`(`**    | *previous sentence*  | Move to the previous COUNT-th beginning of a sentence or paragraph.                          | `evil-backward-sentence-begin`       |
| **`)`**    | *next sentence*      | Move to the next COUNT-th beginning of a sentence or end of a paragraph.                     | `evil-forward-sentence-begin`        |
| **`-`**    | *previous line*      | Move the cursor COUNT lines up on the first non-blank character.                             | `evil-previous-line-first-non-blank` |
| **`_`**    | *line*               | Move the cursor COUNT-1 lines down on the first non-blank character.                         | `evil-next-line-1-first-non-blank`   |
| **`+`**    | *next line*          | Move the cursor COUNT lines down on the first non-blank character.                           | `evil-next-line-first-non-blank`     |
| **`=`**    | *indent*             | Indent text.                                                                                 | `evil-indent`                        |
| **`[`**    | *previous*           | (prefix)                                                                                     |                                      |
| **`]`**    | *next*               | (prefix)                                                                                     |                                      |
| **`{`**    | *previous paragraph* | Move to the beginning of the COUNT-th previous paragraph.                                    | `evil-backward-paragraph`            |
| **`}`**    | *next paragraph*     | Move to the end of the COUNT-th next paragraph.                                              | `evil-forward-paragraph`             |
| **`\\`**   |                      |                                                                                              |                                      |
| **(pipe)** |                      |                                                                                              |                                      |
| **`;`**    |                      |                                                                                              |                                      |
| **`:`**    |                      |                                                                                              |                                      |
| **`'`**    |                      | Go to the line of the marker specified by CHAR.                                              | `evil-goto-mark-line`                |
| **`"`**    |                      | Use REGISTER for the next command.                                                           | `evil-use-register`                  |
| **`,`**    | *major mode*         | (prefix)                                                                                     |                                      |
| **`.`**    |                      |                                                                                              |                                      |
| **`<`**    |                      |                                                                                              |                                      |
| **`>`**    |                      |                                                                                              |                                      |
| **`/`**    |                      |                                                                                              |                                      |
| **`?`**    |                      |                                                                                              |                                      |
