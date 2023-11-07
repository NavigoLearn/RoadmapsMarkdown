# 6. Working with Text Files
- Working with files in the terminal might be required especially when working with servers.

## 6.A Text Editors
- There's many diffrent text editors that you can use in the terminal with different features and shortcuts.

### 6.AA Vim / Vi
- Vim is a text editor that is very popular among developers.
- It has a lot of features and shortcuts that make it very powerful. It is also very customizable. But it also requires an upfront investment to learn.
- [Gamified Tutorial - Vim Adventures](https://vim-adventures.com)

### 6.AB Nano
- Nano is a text editor that is made to be very simple and easy to use.
- It is very easy to learn and use. But it is not as powerful as Vim.
- [Documentation - Nano](https://www.nano-editor.org/docs.php)

### 6.AC Emacs
- Have you ever thought about your operating system as a text editor? Emacs is a text editor that is also an operating system.
- Emacs has a lot of powerful features and shortcuts. It is also very customizable. But it can be overwhelming to learn.
- [Tour - GNU Emacs](https://www.gnu.org/software/emacs/tour)

### 6.AD Micro
- The new kid on the block. Micro is a terminal-based text editor that is easy to use and has a lot of features. If you liked the simplicity of Nano but wanted more features, Micro is for you.
- It is straightforward to learn and use. But it is not as powerful as Vim. You may think of it as a modern Nano with highlighting, mouse, and plugin support.
- [Documentation - Micro](https://micro-editor.github.io)

## 6.B Text Manipulation
- `cut` allows you to cut out sections of each line of a file.
  ex: `cut -d " " -f 1 file.txt` (cuts out the first column of a file)
- `paste` allows you to merge lines of files.
  ex: `paste file1.txt file2.txt` (merges the lines of two files)
- `sort` allows you to sort the lines of a file.
  ex: `sort file.txt` (sorts the lines of a file)
- `uniq` allows you to remove duplicate lines from a file.
  ex: `uniq file.txt` (removes duplicate lines from a file)
- [Documentation - cut](https://manpages.org/cut)
- [Documentation - paste](https://manpages.org/paste)
- [Documentation - sort](https://manpages.org/sort)
- [Documentation - uniq](https://manpages.org/uniq)

## 6.C Text Formatting
- `fmt` allows you to format the lines of a file.
  ex: `fmt file.txt` (formats the lines of a file)
- `pr` allows you to format the pages of a file.
  ex: `pr file.txt` (formats the pages of a file)
- `column` allows you to format the columns of a file.
  ex: `column -t file.txt` (formats the columns of a file)
- [Documentation - fmt](https://manpages.org/fmt)
- [Documentation - pr](https://manpages.org/pr)
- [Documentation - column](https://manpages.org/column)

# 6.D Text Comparison
- `diff` allows you to compare two files.
  ex: `diff file1.txt file2.txt` (compares two files)
- `comm` allows you to compare two sorted files.
  ex: `comm file1.txt file2.txt` (compares two sorted files)
- [Documentation - diff](https://manpages.org/diff)
- [Documentation - comm](https://manpages.org/comm)