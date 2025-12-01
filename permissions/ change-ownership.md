# How to Change File Ownership in Linux (chown)

This guide explains how to change the owner of a file or directory.

---

## ✅ Step 1: Check current ownership
```bash
ls -l file.txt
```

---

## ✅ Step 2: Change owner of a file
```bash
sudo chown devuser1 file.txt
```

---

## ✅ Step 3: Change owner of a directory (recursive)
```bash
sudo chown -R devuser1 /project
```

---

## ✅ Step 4: Change both owner and group
```bash
sudo chown devuser1:devteam file.txt
```

---

## ✅ Verify
```bash
ls -l file.txt
```
