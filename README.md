# Introduction of Linux  <sub><img width="40" height="44" alt="image" src="https://github.com/user-attachments/assets/66051fa6-8716-4291-b3b1-3a176fa051b4" /></sub>

- Linux is not OS, Linux is only Kernal. It's OG OS is GNU developed by Richard Stallman, Linux Kernel is developed by Linus Tarvald

- It is Open Source Linux-based Operating System. 

- Developed for penetration testing (A security test for System safety), Computer Forensics  and ethical hacking.

- Networking is Disabled out-of-the-box for maximum sercurity.


## Demo: Login and System Documentation

1. Connecting Linux in Windows using RDP (Remote Desktop Protocol)

2. Remote text mode login with SSH (Secure SHell)

3. Connecting remote Ubuntu Machine using SSH command in Windows

```bash
SSh aaron@10.0.0.81
# user_name@IP_address'

```

### 1. Built-in System Docimentation


There are lots of built-in commands are there. We are just look into it.

1. ls command

```bash
ls --help
# it helps to find list of information about arguments like -a, -i,..
```

#### It displays like paging. 
#### We can move it up and down.
#### press "q" to exit the page.

2. --help

```bash
jornalctl --help
# It reads the System logs.
```

2. man

- To know manul about a command use "man" command following the the Command name.

```bash
man jornalctl
# It shows Name, Syntax, Description and Examples of the command 
```

- Now, Some times we will have two man pages with same name

- Eg: printf - is a command, printf() is a function

- that's why we look it into man command like the following

```bash
man man
# It shows section no. of the manual.
```
using that sections we use like following:


```bash
man 1 printf
# shell command
