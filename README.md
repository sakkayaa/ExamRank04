# 🐚 Exam Rank 04 — Microshell

A compact C command interpreter built as 42 exam practice. It executes programs, supports pipes (`|`) and command separators (`;`), and includes a built-in `cd` command.

## ⚙️ Build

```bash
cc -Wall -Wextra -Werror microshell/microshell.c -o microshell-bin
```

## 🚀 Example

```bash
./microshell-bin /bin/echo Hello '|' /usr/bin/wc -c
```

Commands are executed by their given path, and the current environment is passed to child processes.
