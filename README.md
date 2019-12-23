# FW


# Easy Way

# 7Zip
```
Simply extract the binaries
```

# Find
```
find . | less
```

# Hexeditor


# Ghidra





# Hard Way

# Binwalk
```
binwalk binary.ext
binwalk -E binary.ext
```
# DD
```
dd if=binary.ext skip=195002 of=linux_fs bs=1 
```
# Unsquashfs
```
unsquashfs linux_fs
```
# Mount
```
umount linux_fs (not done)
```
# Find
```
find . | less
```
