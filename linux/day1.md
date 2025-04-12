# 📅 Day 1 – Linux Basics: Getting Started

📂 **Folder:** `day01-linux-basics`

---

## 🧠 What is Linux?

Linux is an open-source, Unix-like operating system kernel that powers:

- Servers (Most web servers use Linux)
- DevOps pipelines
- Cloud infrastructure (AWS, GCP, Azure)
- Mobile (Android uses Linux Kernel)

🔁 **Why Linux for DevOps?**

- Automation (Scripting & CLI tools)
- Remote server management via SSH
- Flexibility & Customization
- Lightweight & fast
- Open-source community support

---

## 🗂️ Linux File System Hierarchy

| Directory | Purpose |
|----------|---------|
| `/`      | Root directory (everything starts here) |
| `/home`  | User directories (e.g., `/home/yash`) |
| `/etc`   | Config files |
| `/var`   | Logs, variable data |
| `/bin`   | Essential user binaries (like `ls`, `cat`) |
| `/usr`   | User utilities & applications |
| `/tmp`   | Temporary files |

> 📌 Tip: Think of the Linux file system as a **tree**, starting from `/`.

---

## 💻 Essential Terminal Commands (Hands-on)

```bash
# Print current working directory
pwd

# List files & folders
ls
ls -la       # long list with hidden files

# Change directory
cd foldername
cd ..        # go one level back
cd ~         # go to home directory

# Create files & folders
touch file.txt
mkdir myfolder

# Move/Rename files
mv file.txt newname.txt
mv file.txt folder/

# Copy files
cp file.txt copy.txt

# Delete files/folders
rm file.txt
rm -r myfolder

# Who am I & system info
whoami
uname -a

# View manual pages
man ls
man cd

# Clear screen
clear
