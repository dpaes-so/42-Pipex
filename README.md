# 42-Pipex
A program that mimics bash pipe behavior

## 🔨 Features
- No limit on number of commands
- First command accepts input from a file
- Writes output to a file
- Supports here_doc mode
---
## 💻 How to Run
Clone and compile the project, then run a command:
```bash
git clone https://github.com/dpaes-so/42-Pipex.git
cd 42-Pipex
make
./pipex file1 "cat" "wc -l" file2

./pipex here_doc LIMITER "cat" "wc -l" output_file
