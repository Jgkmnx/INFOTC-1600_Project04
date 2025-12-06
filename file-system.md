# The Linux File System


## File System Overview
The Linux file system controls how data is stored, organized, and accessed on storage devices. In Linux, everything is treated as a file including documents, programs, devices, and system resources.  

Instead of using drive letters like Windows, Linux uses mount points where storage devices attach into a single directory tree starting at the root directory `/`. This unified structure allows all files and hardware resources to appear organized under one hierarchy.


### Linux layered file system architecture:

- **Logical File System** — handles basic file operations like opening and reading files
- **Virtual File System (VFS)** — provides a common interface so different file systems can work together
- **Physical File System** — manages how data is physically stored on disk

Together, these layers ensure that data is stored efficiently while remaining easy for users to access.


---

## Key Directories

| Directory | Purpose                          |
|----------|----------------------------------|
| `/`      | Root of the file system         |
| `/home`  | User home directories           |
| `/etc`   | Configuration files             |
| `/var`   | Variable data (logs, spool, etc.) |
| `/bin`   | Essential user commands         |
| `/usr`   | User programs and data          |

---


## File Paths
- **Absolute paths** start at the root `/`
- **Relative paths** are based on your current location

  
## Terminal Navigation Examples For Users:
```bash
pwd          # show current directory
ls           # list files and folders
cd /home     # move to /home directory
cd ..        # go up one directory
cd ~         # go to your home directory
```

### Sorces 
[1] [https://www.geeksforgeeks.org/linux-unix/linux-file-system/#linux-file-systems](https://www.geeksforgeeks.org/linux-unix/linux-file-system/#linux-file-systems)

  
### Navigation
- [Back to Home](README.md)
- [Next:Basic Linux Commands](basic-commands.md)
