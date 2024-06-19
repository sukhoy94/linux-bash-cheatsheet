# Linus bash CheatSheet

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
