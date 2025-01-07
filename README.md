# vim-cheat-sheet

## Cursor Movement

| Command              | Mode   | Description                                                                                                                                                                           |
| -------------------- | ------ | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| `h`, `j`, `k`, `l`   | Normal | Move the cursor: `h` (left), `j` (down), `k` (up), and `l` (right).                                                                                                                   |
| `w`, `W`             | Normal | Move the cursor to the start of the next word (`w` considers punctuation; `W` skips it).                                                                                              |
| `e`, `E`             | Normal | Move the cursor to the end of the current or next word (`e` considers punctuation; `E` skips it).                                                                                     |
| `b`, `B`             | Normal | Move the cursor to the start of the previous word (`b` considers punctuation; `B` skips it).                                                                                          |
| `f{char}`, `F{char}` | Normal | Move the cursor to the next (`f`) or previous (`F`) occurrence of a character on the current line.                                                                                    |
| `t{char}`, `T{char}` | Normal | Move the cursor right before the next (`t`) or previous (`T`) occurrence of a character on the current line.                                                                          |
| `0`, `^`, `$`        | Normal | Move the cursor to the beginning of the line (`0`), the first non-whitespace character of the line (`^`), or the end of the line (`$`).                                               |
| `G`, `[count]G`      | Normal | Move the cursor to the end of the file (`G`) or to a specific line number (`[count]G`). Invalid line numbers move to the nearest valid line (last or first).                          |
| `gg`, `[count]gg`    | Normal | Move the cursor to the first non-blank character of the first line (`gg`) or a specified line (`[count]gg`). If the target line is empty, the cursor moves to the start of that line. |
| `#`, `*`             | Normal | Move the cursor to the previous (`#`) or next (`*`) occurrence of the word under the cursor.                                                                                          |
| `(`, `)`             | Normal | Move the cursor to the beginning of the previous sentence (`(`) or the next sentence (`)`).                                                                                           |
| `%`                  | Normal | Move the cursor to the matching pair of parentheses, brackets, or braces.                                                                                                             |

## Editing

| Command        | Mode   | Description                                                                                                                      |
| -------------- | ------ | -------------------------------------------------------------------------------------------------------------------------------- |
| `x`, `X`       | Normal | Delete the character under the cursor (`x`) or before the cursor (`X`).                                                          |
| `d`, `D`       | Normal | Delete from the cursor to a motion (`d`) or to the end of the line (`D`).                                                        |
| `c`, `C`, `c$` | Normal | Change (delete and enter Insert mode) from the cursor to a motion (c) or to the end of the line (C, c$).                         |
| `y`, `Y`       | Normal | Yank (copy) text from the cursor to a motion (`y`) or yank the entire line (`Y`).                                                |
| `r`, `R`       | Normal | Replace a single character under the cursor (`r`) or enter Replace mode under the cursor to overwrite multiple characters (`R`). |
| `~`            | Normal | Switch the case of the character under the cursor.                                                                               |
| `p`, `P`       | Normal | Paste the text from the unnamed register after (`p`) or before (`P`) the cursor.                                                 |

## Entering Insert Mode

| Command  | Mode   | Description                                                                              |
| -------- | ------ | ---------------------------------------------------------------------------------------- |
| `i`, `I` | Normal | Enter Insert mode before the cursor (`i`) or at the beginning of the current line (`I`). |
| `a`, `A` | Normal | Enter Insert mode after the cursor (`a`) or at the end of the current line (`A`).        |
| `o`, `O` | Normal | Enter Insert mode and open a new line below (`o`) or above (`O`) the current line.       |

## Miscellaneous

| Command | Mode         | Description            |
| ------- | ------------ | ---------------------- |
| `Esc`   | Any          | Return to Normal mode. |
| `:w`    | Command-line | Save the current file. |
| `:q`    | Command-line | Quit Vim.              |
