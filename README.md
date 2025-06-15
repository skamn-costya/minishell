# Minishell

![image](https://github.com/user-attachments/assets/077ce09d-4a3f-4273-832f-544c29ef6fcc)

## ✅ Mandatory Features
The shell implements the following features:
- A prompt that reads user input
- Lexical analysis and command parsing
- Arrow key history navigation
- Command separators (`;`)
- Pipes (`|`)
- Redirections:
  - Input redirection (`<`)
  - Output redirection (`>`)
  - Append redirection (`>>`)
  - Here-document (`<<`)
- Built-in commands:
  - `echo`
  - `cd`
  - `pwd`
  - `export`
  - `unset`
  - `env`
  - `exit`
- Execution of binary commands using `execve`
- Environment variables (`$VAR`)
- Return status variable (`$?`)
- Quoting rules (handling of `"` and `'`)
- Signal handling (`ctrl-C`, `ctrl-D`, `ctrl-\`)
- Proper memory and file descriptor management  

## 🧠 Learning Outcomes
Through this project, we learned:  
How shells interpret and execute commands  
How to manage processes with fork, execve, and wait  
File descriptor duplication and redirection with dup2  
Signal handling using signal and sigaction  
Parsing and managing environment variables  
Memory management and debugging  

## 🧪 Testing
The shell has been tested with:  
Built-in and external commands  
Pipes and redirections combinations  
Quotes and environment variable expansion  
Edge cases (invalid syntax, missing files, permission errors)  

## 🎁 Bonus
If you completed the bonus part, include what’s implemented here:
- Logical operators (&&, ||)
- Wildcard expansion (*)

## 👤 Authors
[[skamn-costya](https://github.com/skamn-costya)]

[[stepskop](https://github.com/stepskop)]
