# 🐧 TryHackMe – Linux Fundamentals Part 1

![Difficulty](https://img.shields.io/badge/Difficulty-Easy-brightgreen)
![Category](https://img.shields.io/badge/Category-Linux-blue)
![Platform](https://img.shields.io/badge/Platform-TryHackMe-red)
![Status](https://img.shields.io/badge/Status-Completed-success)

---

# 📝 Overview

**Linux Fundamentals Part 1** introduces the essential concepts of the Linux operating system and its command-line interface (CLI). The room focuses on navigating the filesystem, interacting with files and directories, searching for information, and understanding shell operators.

This room provides the foundational Linux knowledge required for Cybersecurity, Penetration Testing, CTFs, and Red Team operations.

---

# 🎯 Learning Objectives

After completing this room, I learned how to:

- Understand the importance of Linux in Cybersecurity.
- Navigate the Linux filesystem efficiently.
- Work with files and directories.
- Use the Linux Terminal (CLI).
- Search for files and text.
- Understand common Linux directories.
- Use Shell Operators.
- Execute basic Linux commands confidently.

---

# 📚 Topics Covered

## 🐧 What is Linux?

Linux is a free and open-source operating system based on Unix.

### Why Linux?

- Free & Open Source
- Stable
- Secure
- Lightweight
- Highly Customizable
- Used by most servers worldwide
- Preferred Operating System for Ethical Hackers & Penetration Testers

---

## 🌍 Where is Linux Used?

Linux powers many systems around the world, including:

- 🌐 Websites & Web Servers
- ☁️ Cloud Infrastructure
- 🚗 Car Entertainment Systems
- 🛒 Point of Sale (POS) Systems
- 🚦 Traffic Lights
- 🏭 Industrial Controllers
- 📱 Smartphones
- 📡 IoT Devices

---

# 💻 Talking to Linux

Linux is primarily controlled through the Command Line Interface (CLI).

## Basic Commands

### `whoami`

Displays the current logged-in user.

```bash
whoami
```

---

### `echo`

Prints text to the terminal.

```bash
echo "Hello World"
```

Example Output:

```text
Hello World
```

---

# 📂 Linux Navigation

## Print Current Directory

```bash
pwd
```

Displays your current location.

---

## List Files

```bash
ls
```

Lists files and folders.

---

## Long Listing

```bash
ls -l
```

Displays detailed information.

---

## Hidden Files

```bash
ls -a
```

Shows hidden files.

---

## Long + Hidden

```bash
ls -la
```

Displays everything.

---

## Change Directory

```bash
cd folder
```

Move into a folder.

---

## Go Back

```bash
cd ..
```

Moves one directory back.

---

## Home Directory

```bash
cd ~
```

Returns to the Home directory.

---

# 📁 File Management

## Create Directory

```bash
mkdir Test
```

---

## Create File

```bash
touch file.txt
```

---

## Delete File

```bash
rm file.txt
```

---

## Delete Empty Directory

```bash
rmdir Test
```

---

## Copy Files

```bash
cp source destination
```

---

## Move / Rename

```bash
mv old.txt new.txt
```

---

## Read File

```bash
cat file.txt
```

Displays the contents of a file.

---

# 📦 Linux Filesystem

| Directory | Purpose |
|-----------|---------|
| `/` | Root Directory |
| `/home` | User Home Directories |
| `/root` | Root User Directory |
| `/etc` | System Configuration Files |
| `/var` | Logs & Variable Data |
| `/tmp` | Temporary Files |
| `/bin` | Essential System Commands |
| `/opt` | Optional Software |

---

# 🔍 Searching in Linux

## Find Files

```bash
find / -name filename
```

Search for files by name.

---

## Search Inside Files

```bash
grep keyword file.txt
```

Search for specific text.

---

## Manual Pages

```bash
man ls
```

Displays the manual page.

---

## Locate Commands

```bash
which python
```

Shows the location of an executable.

---

# ⚙️ Shell Operators

## AND Operator (`&&`)

```bash
command1 && command2
```

Runs the second command only if the first command succeeds.

---

## OR Operator (`||`)

```bash
command1 || command2
```

Runs the second command only if the first command fails.

---

## Pipe (`|`)

```bash
command1 | command2
```

Passes the output of one command as input to another.

---

## Redirect Output (`>`)

```bash
command > file.txt
```

Overwrites the contents of a file.

---

## Append Output (`>>`)

```bash
command >> file.txt
```

Appends output to a file without overwriting existing content.

---

# ⭐ Important Commands

| Command | Description |
|---------|-------------|
| `pwd` | Show current directory |
| `whoami` | Show current user |
| `echo` | Print text |
| `history` | Show command history |
| `clear` | Clear terminal |
| `ls` | List files |
| `ls -l` | Detailed file listing |
| `ls -a` | Show hidden files |
| `ls -la` | Detailed + hidden files |
| `cd` | Change directory |
| `mkdir` | Create directory |
| `touch` | Create file |
| `cp` | Copy files |
| `mv` | Move or rename files |
| `rm` | Delete files |
| `rmdir` | Delete empty directory |
| `cat` | Display file contents |
| `find` | Search for files |
| `grep` | Search text inside files |
| `man` | View manual pages |
| `which` | Locate executable |
| `clear` | Clear terminal |

---

# 🧠 Key Takeaways

- Linux is the most widely used operating system in Cybersecurity.
- Mastering the Linux Terminal is essential for every Penetration Tester.
- Understanding the Linux filesystem makes navigation much easier.
- File management commands are used daily.
- Searching with `find` and `grep` saves significant time.
- Shell Operators improve productivity by combining commands.

---

# 🎓 Skills Gained

- Linux Fundamentals
- Linux Command Line (CLI)
- Filesystem Navigation
- File & Directory Management
- Searching with `find` and `grep`
- Shell Operators
- Basic Linux Administration

---

# 🏁 Conclusion

Linux Fundamentals Part 1 provided a solid introduction to the Linux operating system and command-line interface. Throughout this room, I learned how to navigate the Linux filesystem, manage files and directories, search for files and content efficiently, and use essential shell operators. These skills form a strong foundation for penetration testing, CTF challenges, Linux administration, and everyday work in cybersecurity.

---

## 🚀 Platform

**TryHackMe**

https://tryhackme.com/
