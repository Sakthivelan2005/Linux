# Creating Copying Moving Deleting (CCMD) on Files and Directories

## 1. Creating
### **Files:**
- To create a file :
```bash
touch Receipt.pdf
#This will create it inside the current Directory
```
- To create it at another location (Absolute Path)
```bash
touch /home/jane/Receipt.pdf
```
- To create it at another location (Relative Path)
```bash
touch ../jane/Receipt.pdf
```


### **Directories:**
- To create a new directory:
```bash
mkdir Receipts
# means make Director6
```

## 2. Copying
### **Files:**
-  To copy a file from one place to another we use:
Syntax:
```bash
cp [source] [destiination]
# Both [] are path names
```

Usage:
```bash
cp Receipt.pdf Receipts/
```
Overview:

<img width="1535" height="862" alt="image" src="https://github.com/user-attachments/assets/8e8c8cd6-1a92-4400-ae78-829398452b35" />


### **Directly:**
- To copy a directory and all its contents to another directory
Syntax:
```bash
cp -r [source] [destination] 
# -r flag tells cp to copy "recursively" means "Process to multiple Directory"
```

Usage: 
```bash
cp -r Receipts/ BackupOfReceipts/
# It creates "BackupOfReceipts" directory if not there.
```
**Overview:**
- If the "BackupOfReceipts" directory is not there. It performs like this:

<img width="1535" height="862" alt="image" src="https://github.com/user-attachments/assets/fb544579-9715-4ef2-a98c-ae33547cfc4e" />

- If already the "BackupOfReceipts" directory is there. It performs like this:

<img width="1535" height="862" alt="image" src="https://github.com/user-attachments/assets/18249e02-7a6b-4772-b34b-78bfe04d640f" />

## 3. Moving
### **Files:**
- To move a File from one place to another:
Syntax:
```bash
mv [source] [destination]
```

Usage: 
```bash
mv Receipt.pdf Receipts/
```

Overview:

<img width="1535" height="862" alt="image" src="https://github.com/user-attachments/assets/16a2de67-174f-4114-9249-62ad665526ef" />

- We can Use this same command for Renaming the File or Directory.

<img width="1535" height="862" alt="image" src="https://github.com/user-attachments/assets/6179afc4-960b-4838-9ba8-2089647a1fdd" />

## 4. Deleting
### **Files:**
- To delete a file we use:
Syntax:
```bash
rm [File-Name]
# rm - ReMove
```

Usage:
```bash
rm Invoice.pdf
```

Overview:

<img width="1535" height="862" alt="image" src="https://github.com/user-attachments/assets/32cc5cbe-ee63-44f9-a272-1e715d7d349a" />

### **Directories:**
- To delete a Directory we use:
Syntax:
```bash
rm [source]
```

Usage:
```bash
rm -r Invoices/
# r - Recursive (Remove multiple files and folder under the mentioned Directory)
```

Overview:

<img width="1535" height="862" alt="image" src="https://github.com/user-attachments/assets/030cd282-d745-4c0c-9a20-2ab7bc4c7a94" />
