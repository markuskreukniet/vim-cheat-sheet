# vim-cheat-sheet

| Command          | Mode         | Description                                                                                                  |
| ---------------- | ------------ | ------------------------------------------------------------------------------------------------------------ |
| h, j, k, l       | Normal       | Move the cursor left, down, up, and right.                                                                   |
| w<char>, W<char> | Normal       | Move the cursor to the start of the next word ('w' considers punctuation; 'W' skips it).                     |
| e<char>, E<char> | Normal       | Move the cursor to the end of the current or next word ('e' considers punctuation; 'E' skips it).            |
| b, B             | Normal       | Move the cursor to the start of the previous word ('b' considers punctuation; 'B' skips it).                 |
| f<char>, F<char> | Normal       | Move the cursor to the next ('f') or previous ('F') occurrence of a character on the current line.           |
| t<char>, T<char> | Normal       | Move the cursor right before the next ('t') or previous ('T') occurrence of a character on the current line. |
| x, X             | Normal       | Delete the character under the cursor ('x') or before the cursor ('X').                                      |
| i, I             | Normal       | Enter Insert mode before the cursor ('i') or at the beginning of the current line ('I').                     |
| a, A             | Normal       | Enter Insert mode after the cursor ('a') or at the end of the current line ('A').                            |
| Esc              | Any          | Return to Normal mode.                                                                                       |
| :w               | Command-line | Save the current file.                                                                                       |
| :q               | Command-line | Quit Vim.                                                                                                    |
