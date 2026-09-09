# Files and Directories

Before Getting into it we should know What is File System Tree, Absolute Path and Relative Path.

1. To list all files and Directories:
```bash
ls -la

```

2. To list all files and Directories, even the ones beginning with a dot:
```bash
ls -a

```

3. To list files and directories from a different location:
```bash
ls /var/log

```

(or)

```bash
ls -l /var/log
# It list in a long listing format which shows more details for each entry
```

4. To list all files and directories also long listing format:
```bash
ls -a -l

```
(or)

```bash
ls -alh
# It doesn't matter which order you put flags, and you don't have to put dash "-" in front of each of them.

# Then -h shows sizes in human-readable format such as KB, MB, or GB

```


## 1. File System Tree

Linux file system tree is the structured, hierarchical way Linux organizes all of its folders and files. 

- Root Directory:
<img width="1919" height="1079" alt="image" src="https://github.com/user-attachments/assets/ac2cc39a-16d0-4598-a17d-7ff91d086c4a" />

- Sub Directory (Branches):
<img width="1919" height="1079" alt="image" src="https://github.com/user-attachments/assets/73da9431-b43d-456b-9005-511f81a67286" />

- Another Sub Directory (Leaves):
<img width="1919" height="1079" alt="image" src="https://github.com/user-attachments/assets/8ff76c8d-f500-470f-93e9-fb96d3c377e4" />

## 2. Absolute Path

To access specific file or directory, we have to specify the Absolute Path.
<img width="1919" height="1079" alt="image" src="https://github.com/user-attachments/assets/41e27c92-bca3-4804-b846-01c5a1cf7c91" />


First thing we have to know that Current Working Directory for that we use:
```bash
pwd
# It shows current Working Directory PWD (Print Working Directory)

# /root
```

### Changing Directory
To change directory we use "cd" command:

1. To change specific directory:
```bash
cd /sub-directory
```

2. To go to Previous Directory:
```bash
cd ..
```
(OR)

```bash
cd -
```

3. To go to Root Directory:
```bash
cd /
```

4. To go to home directory
```bash
cd 
```




## 3. Relative Path

We can access specific file or directory without typing previous directory from the Parent Directory.


<img width="1919" height="1079" alt="image" src="https://github.com/user-attachments/assets/c64e4b22-3f75-440f-8ace-4544d8062945" />
