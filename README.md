# 42-Pipex
A program that mimics bash pipe behavior

## 🔨 Features
- no limits of commands
- the first command accepts input from a file
- writes the output to a outfile
- handles the here_doc mode
---
## 💻 How to Run
Clone and compile the project, then run a command:
```bash
git clone https://github.com/dpaes-so/42-Pipex.git
cd pipex
make
./pipex file1 "cat" "wc -l" file2

