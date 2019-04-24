<!-- markdown-toc start - Don't edit this section. Run M-x markdown-toc-refresh-toc -->
**Table of Contents**

- [spacemacs](#spacemacs)
    - [Key bindings](#key-bindings)
        - [Lowercase letters](#lowercase-letters)
        - [Uppercase letters](#uppercase-letters)
        - [Numbers](#numbers)
        - [Punctuation](#punctuation)

<!-- markdown-toc end -->
# spacemacs

## Key bindings

### Lowercase letters

| Key    | Mnemonic     | Description                                                     | Function                   |
| ------ | --------     | --------------------------------------------------------------- | ------------------------   |
| a      | *append*     | Switch to Insert state just after point.                        | `evil-append`              |
| b      | *backward*   | Move the cursor to the beginning of the COUNT-th previous word. | `evil-backward-word-begin` |
| c      | *change*     | Change text from BEG to END with TYPE.                          | `evil-change`              |
| d      | *delete*     | Delete text from BEG to END with TYPE.                          | `evil-delete`              |
| e      | *end*        | Move the cursor to the end of the COUNT-th next word.           | `evil-forward-word-end`    |
| f      | *find*       | Move to the next COUNT’th occurrence of CHAR.                   | `evil-find-char`           |
| g      | *goto*       | (prefix)                                                        |                            |
| h      |              | Move cursor to the left by COUNT characters.                    | `evil-backward-char`       |
| i      | *insert*     | Switch to Insert state just before point.                       | `evil-insert`              |
| j      |              | Move the cursor COUNT lines down.                               | `evil-next-line`           |
| k      |              | Move the cursor COUNT lines up.                                 | `evil-previous-line`       |
| l      |              | Move cursor to the right by COUNT characters.                   | `evil-forward-char`        |
| m      | *mark*       | Set the marker denoted by CHAR to position POS.                 | `evil-set-marker`          |
| n      | *next*       | Goes to the next occurrence.                                    | `evil-ex-search-next`      |
| o      | *open*       | Insert a new line below point and switch to Insert state.       | `evil-open-below`          |
| p      | *paste*      | Disable paste transient state if there is more than 1 cursor.   | `evil-mc-paste-after`      |
| q      |              | Record a keyboard macro into REGISTER.                          | `evil-record-macro`        |
| r      | *replace*    | Replace text from BEG to END with CHAR.                         | `evil-replace`             |
| s      | *substitute* | Change a character.                                             | `evil-substitute`          |
| t      | *to*         | Move before the next COUNT’th occurrence of CHAR.               | `evil-find-char-to`        |
| u      | *undo*       | Undo changes.                                                   | `evil-tree-undo`           |
| v      | *visual*     | Characterwise selection.                                        | `evil-visual-char`         |
| w      | *word*       | Move the cursor to the beginning of the COUNT-th next word.     | `evil-forward-word-begin`  |
| x      | *cross*      | Delete next character.                                          | `evil-delete-char`         |
| y      | *yank*       | Saves the characters in motion into the kill-ring.              | `evil-yank`                |
| z      | *scroll*     | (prefix)                                                        |                            |

### Uppercase letters

| Key    | Mnemonic  | Description                                                     | Function                   |
| ------ | --------  | --------------------------------------------------------------- | ------------------------   |
| A      | *append*  | Switch to Insert state at the end of the current line.          | `evil-append-line`         |
| B      | *back*    | Move the cursor to the beginning of the COUNT-th previous WORD. | `evil-backward-WORD-begin` |
| C      | *change*  | Change to end of line.                                          | `evil-change-line`         |
| D      | *delete*  | Delete to end of line.                                          | `evil-delete-line`         |
| E      | *end*     | Move the cursor to the end of the COUNT-th next WORD.           | `evil-forward-WORD-end`    |
| F      | *find*    | Move to the previous COUNT’th occurrence of CHAR.               | `evil-find-char-backward`  |
| G      |           |                                                                 |                            |
| H      |           |                                                                 |                            |
| I      |           |                                                                 |                            |
| J      |           |                                                                 |                            |
| K      |           |                                                                 |                            |
| L      |           |                                                                 |                            |
| M      |           |                                                                 |                            |
| N      |           |                                                                 |                            |
| O      |           |                                                                 |                            |
| P      |           |                                                                 |                            |
| Q      |           |                                                                 |                            |
| R      | *replace* | Enable Replace state. Disable with negative ARG.                | `evil-replace-state`       |
| S      |           |                                                                 |                            |
| T      |           |                                                                 |                            |
| U      |           |                                                                 |                            |
| V      |           |                                                                 |                            |
| W      |           |                                                                 |                            |
| X      |           |                                                                 |                            |
| Y      |           |                                                                 |                            |
| Z      |           |                                                                 |                            |

### Numbers

| Key    | Mnemonic   | Description                                                     | Function                 |
| ------ | --------   | --------------------------------------------------------------- | ------------------------ |
| 0      |            |                                                                 |                          |
| 1      |            |                                                                 |                          |
| 2      |            |                                                                 |                          |
| 3      |            |                                                                 |                          |
| 4      |            |                                                                 |                          |
| 5      |            |                                                                 |                          |
| 6      |            |                                                                 |                          |
| 7      |            |                                                                 |                          |
| 8      |            |                                                                 |                          |
| 9      |            |                                                                 |                          |

### Punctuation

| Key    | Mnemonic | Description                                                     | Function                 |
| ------ | -------- | --------------------------------------------------------------- | ------------------------ |
| !      |          |                                                                 |                          |
| "      |          |                                                                 |                          |
| #      |          |                                                                 |                          |
| $      |          |                                                                 |                          |
| %      |          |                                                                 |                          |
| &      |          |                                                                 |                          |
| '      |          |                                                                 |                          |
| (      |          |                                                                 |                          |
| (pipe) |          |                                                                 |                          |
| )      |          |                                                                 |                          |
| +      |          |                                                                 |                          |
| ,      |          |                                                                 |                          |
| -      |          |                                                                 |                          |
| .      |          |                                                                 |                          |
| /      |          |                                                                 |                          |
| :      |          |                                                                 |                          |
| ;      |          |                                                                 |                          |
| <      |          |                                                                 |                          |
| =      |          |                                                                 |                          |
| >      |          |                                                                 |                          |
| ?      |          |                                                                 |                          |
| @      |          | Execute keyboard macro MACRO, COUNT times.                      | `evil-execute-macro`     |
| \*     |          |                                                                 |                          |
| \[     |          |                                                                 |                          |
| \\     |          |                                                                 |                          |
| \]     |          |                                                                 |                          |
| \_     |          |                                                                 |                          |
| \`     |          |                                                                 |                          |
| \{     |          |                                                                 |                          |
| \}     |          |                                                                 |                          |
| ^      |          |                                                                 |                          |
| ~      |          |                                                                 |                          |
