# Methodology

```
Once the bins are extract
```

# Find the bins !

```
/bin
/usr/bin
/sbin
/usr/local/bin
/usr/local/sbin
```

# Script - Find Bins
```
for lol in `find .`; do /usr/arm-linux-gnueabi/bin/readelf -h $lol; done
```

# Script - Search for vulnerable functions
```
for lol in `ls`; do /usr/arm-linux-gnueabi/bin/readelf -Ws $lol;done |  grep strcpy
```


# Fun
```
Strcpy(destination, source)
If source is larger than destination, buffer is overwritten.
```
