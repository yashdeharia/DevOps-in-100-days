# 🚀 Day 5 of 100 Days of DevOps

## 📅 Date:
April 15, 2025

## 📘 Topic:
Linux - User & Group Management

## 🧠 What I Learned:

## AWS E2 -- Free tier instance
- Made a AWS E2 Ubuntu instance.
- connect to local via SSH client.

### 👤 User Management:
- `sudo`: Execute commands with superuser privileges.
- `useradd`: Add new user accounts.
- `whoami`: Display the current logged-in user.
- `su`: Switch to another user account.
- `passwd`: Change user passwords.
- `userdel`: Delete user accounts.

### 👥 Group Management:
- `groupadd`: Create new groups.
- `gpasswd -a`: Add a user to a group.
- `gpasswd -m`: Set multiple users as group members.
- `groupdel`: Delete groups.

## 🔁 Commands Practiced:
```bash
sudo command
useradd username
whoami
su - username
passwd username
userdel username
groupadd groupname
gpasswd -a username groupname
gpasswd -m user1,user2 groupname
groupdel groupname
chmod 400 /path/to/key.pem
ssh -i /path/to/key.pem ubuntu@my-ec2-public-dns
