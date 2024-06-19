# Linus bash CheatSheet

## Table of Contents
1. [Copy All Files from One Folder to Another](#copy-all-files-from-one-folder-to-another)
    - [Including Hidden Files](#including-hidden-files)
2. [Listing Files](#listing-files)
    - [By Modification Time (newest first)](#by-modification-time-newest-first)
    - [By Size (largest first)](#by-size-largest-first)
3. [Find a File by Its Filename in a Directory](#find-a-file-by-its-filename-in-a-directory)

### Copy all files from one folder to another 

```
cp -r /source_dir/* /destination_dir/
```

To copy also hidden files (like .env, .gitignore):

```
cp -r /source_dir/{*,.*} /destination_dir/
```

### Listing files:

The `ls` command in Linux is used to list directory contents. You can sort the output of `ls` in various ways by using different options.

1. By Modification Time (newest first):
```
ls -lt
```

2. By Size (largest first):
```
ls -lS
```

### Find a file by it's filename in a directory
Basic Syntax
```
find /path/to/directory -name "*part_of_name*"
```
Find files containing "log" in their names:
```
find /path/to/directory -name "*log*"
```

