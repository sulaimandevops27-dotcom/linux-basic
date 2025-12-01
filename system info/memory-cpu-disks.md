# 🔹 Check System Info and Install Java on Linux

This guide explains how to check system information (memory, CPU, disk usage, uptime) and install Java.

---

## ✅ Step 1: Check Hostname and Operating System
```bash
hostname
lsb_release -d
```

---

## ✅ Step 2: Check CPU Information
```bash
lscpu | grep -E "Model name|Architecture|CPU\(s\)"
```

---

## ✅ Step 3: Check Memory Usage
```bash
free -h
```

---

## ✅ Step 4: Check Disk Usage
```bash
df -h | grep -E '^/dev/'
```

---

## ✅ Step 5: Check System Uptime
```bash
uptime -p
```

---

## 📌 Optional: Check Top Processes by CPU and Memory
```bash
ps -eo pid,ppid,cmd,%mem,%cpu --sort=-%cpu | head -n 6
```

---

## ✅ Step 6: Update Package List
```bash
sudo apt update
```

---

## ✅ Step 7: Install Java (OpenJDK 11)
```bash
sudo apt install -y openjdk-11-jdk
```

---

## 📌 Optional: Install Java 17
```bash
sudo apt install -y openjdk-17-jdk
```

---

## ✅ Step 8: Check Java Version
```bash
java -version
```

---

## 🎉 All checks and installation complete!

