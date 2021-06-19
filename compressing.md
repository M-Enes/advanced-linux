## There are 3 different methods for compressing

> **compress** (extension .Z)  
compress - *compressing*  
uncompress - *uncompressing*

> **gzip** (extension .gz)  
gzip - *compressing*  
gunzip - *uncompressing*

> **bzip2** (extension .bz2)  
bzip2 - *compressing*  
bunzip2 - *uncompressing*

## Compressing with tar

### Creating archives
`tar -zcvf archive.tar.gz file1 file2`  
Explaining parameters  
- -z for zip
- -c for create
- -v for verbose (graphical output)
- -f for file

### Extracting archives
`tar -zxvf archive.tar.gz`  
-x parameter for extracting

### Viewing files in archive
`tar -ztvf archive.tar.gz`  
-t parameter for list content