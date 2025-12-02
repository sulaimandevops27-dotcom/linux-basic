# How to Change Group Ownership  (chgrp)

## ✅ Step 1: Check group of a file
```bash
ls -l file.txt
```

## ✅ Step 2: Change group of a file
```bash
sudo chgrp devteam file.txt
```

## ✅ Step 3: Change group of a directory (recursive)
```bash
sudo chgrp -R devteam /project
```

## ✅ Verify
```bash
ls -l file.txt
```
