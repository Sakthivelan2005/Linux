# <sup> System Documentation </sup>  <img width="52" height="52" alt="image" src="https://github.com/user-attachments/assets/cccbcb56-327f-4e13-b4dc-53c49aa4f153" />


Imagine, you forgot the name of the command that creates a new Directory.

## apropos (searching)

apropos is a command that search through man (manual) pages.

```bash
apropos director
# It searches words like directory, directories, and so on.

```
Note: apropos relies on a database. So If you run for first time it through you an error.

To create it manually with:

```bash
sudo mandb
```

So, Now the aprops will work

```bash
apropos director

# output:

# basename (1)         - strip directory and suffix from file...
# chroot (8)           - run command or interactive shell wit...
# cp (1)               - copy files and directories
# dbus-cleanup-sockets (1) - clean up leftover sockets in a d...
# dir (1)              - list directory contents
# docker-container-diff (1) - Inspect changes to files or dir...
# docker-diff (1)      - Inspect changes to files or director...
# docker-plugin-create (1) - Create a plugin from a rootfs an...

# --More--

```

To get specific sections in the search:

```bash
apropos -s 1,8 direct

# output:

# basename (1)         - strip directory and suffix from file...
# chroot (8)           - run command or interactive shell wit...
# cp (1)               - copy files and directories
# dbus-cleanup-sockets (1) - clean up leftover sockets in a d...
# dir (1)              - list directory contents
# docker-container-diff (1) - Inspect changes to files or dir...
# docker-diff (1)      - Inspect changes to files or director...
# docker-plugin-create (1) - Create a plugin from a rootfs an...
# find (1)             - search for files in a directory hier...

# --More--

```



## Suggestion & Auto-completion

1. 
```bash
systemc  # Then Press TAB
# It performs Auto-completion as:
systemctl
```

2. 
```bash
systemctl # then Press TAB + TAB
# It suggest which word can type after this like

# output:

# add-requires            list-timers
# add-wants               list-unit-files
# bind                    list-units
# cancel                  log-level
# cat                     log-target
# condreload              mask
# condrestart             mount-image
# condstop                poweroff
# daemon-reexec           preset
# daemon-reload           preset-all
# default                 reboot
# disable                 reenable
# edit                    reload
# emergency               reload-or-restart
# enable                  rescue
# exit                    reset-failed

# --More--
```

3. 
```bash
systemctl list-dep # Then Press TAB

# It automatically type to:
systemctl list-dependencies
```

These will be huge time saver in the long run.


## Same in Filenames or directory names.

1. Try
```bash
ls /u # Then Press tab
# It auto-completes to:
ls /usr/
```
 (or)

```bash
ls /usr/ # Then Press TAB + TAB
# IT suggest  sub-directories like:

# bin/     include/ lib32/   libexec/ local/   share/
# games/   lib/     lib64/   libx32/  sbin/    src/

```



