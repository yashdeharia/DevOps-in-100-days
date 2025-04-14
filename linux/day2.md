# 🚀 Day 2: Linux Basics – File Operations & Navigation (continued)

## 🔍 What I Learned

### 📁 Linux File System Overview
- `/` → Root directory (everything starts here)
- `/home` → User directories
- `/etc` → Configuration files
- `/var` → Logs and variable data
- `/usr` → User installed software

---

### 🧠 Key Commands Practiced

| Command         | Description                                |
|-----------------|--------------------------------------------|
| `pwd`           | Print working directory                    |
| `cd <dir>`      | Change directory                           |
| `ls -l`         | List files in long format                  |
| `ls -a`         | List all files including hidden ones       |
| `mkdir <dir>`   | Make a new directory                       |
| `touch <file>`  | Create a new empty file                    |
| `cp <src> <dst>`| Copy files/directories                     |
| `mv <src> <dst>`| Move or rename files                       |
| `rm <file>`     | Delete a file                              |
| `rm -r <dir>`   | Recursively delete directory               |
| `cat`           | View file contents                         |
| `nano`, `vim`   | Edit files from terminal                   |

---

## 🛠️ Hands-On Task

Created a `devops-practice` folder and:
- Made nested directories using `mkdir -p`
- Created and moved files with `touch`, `mv`, and `cp`
- Practiced viewing and editing files using `cat` and `nano`

```bash
mkdir -p ~/devops-practice/linux-day2/test
cd ~/devops-practice/linux-day2
touch file1.txt
cp file1.txt test/file2.txt
mv file1.txt renamed.txt
cat renamed.txt
