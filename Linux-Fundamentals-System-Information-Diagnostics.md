# Linux Fundamentals — System Information & Diagnostics

## 📌 Target Information
* **IP Address:** 10.129.251.77
* **User:** htb-student
* **Connection:** `ssh htb-student@10.129.251.77`

---

## 🛠️ Questions & Solutions

### 1. Find out the machine hardware name and submit it as the answer.
* **Command:** `uname -m`
* **Answer:** `x86_64`

### 2. What is the path to htb-student's home directory?
* **Command:** `echo $HOME` or `pwd`
* **Answer:** `/home/htb-student`

### 3. What is the path to the htb-student's mail?
* **Command:** `echo $MAIL`
* **Answer:** `/var/mail/htb-student`

### 4. Which shell is specified for the htb-student user?
* **Command:** `grep "htb-student" /etc/passwd` or `echo $SHELL`
* **Answer:** `/bin/bash`

### 5. Which kernel release is installed on the system? (Format: 1.22.3)
* **Command:** `uname -r`
* **Answer:** `4.15.0`

### 6. What is the name of the network interface that MTU is set to 1500?
* **Command:** `ip a` or `ifconfig`
* **Answer:** `ens192`
