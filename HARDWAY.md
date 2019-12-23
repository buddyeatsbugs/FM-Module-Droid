# Hard Way

# Binwalk
```
binwalk binary.ext
binwal -e binary.ext
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
