# 🚀 Day 3 of 100 Days of DevOps

 

## 📘 Topic:
Linux - Login, Disk Usage & Process Management

## 🧠 What I Learned:

Note:
 To practice you can make EC2 instance using AWS free tier. 

### 🔐 Login-related:
- `ssh`: Securely connected to remote systems
  - SSH (Secure Shell) allows encrypted access to remote servers
  - Used to log in and run commands on another machine over the network
  - Default port is 22
  - Key-based authentication is more secure than password-based login

### 💽 Disk Usage:
- `df`: Checked disk space usage on mounted filesystems
- `du`: Measured disk usage of files and directories

### ⚙️ Process Management:
- `ps`: Viewed running processes
- `top`: Real-time system performance monitoring
- `fuser`: Identified processes using files or sockets
- `kill`: Terminated processes by PID
- `nohup`: Ran commands immune to hangups (useful for background processes)
- `free`: Displayed memory usage
- `vmstat`: System performance stats like memory, CPU, and I/O

## 🔁 Commands Practiced:
```bash
ssh user@host
df -h
du -sh *
ps aux
top
fuser -k filename
kill -9 PID
nohup command &
free -m
vmstat 1 5
