# Simple command to know

**ls** 

`ls` : list content of current directory

`ls -la`: list files from current directory icluding hidden files along with permission

### Options

```bash

`-a` : show all files, including hidden

`-l` : use long listing format (permission,owner,size,date, ...)

```


`pwd` : Display current directories

`cd` : change directory

`mkdir` : used to create directory/folder

`touch` : used to create files

`cp` : used to copy files or directory 

**rm**

*syntax * : rm file or folder name

`rm` : used to remove files

`rmdir` : used to remove empty directory

`rm -r` : used to remove directory containing files

`rm -rf` : used to remove directory permanently

`rm -rf --no-preserve-root` : used to delete or destroy entire system directory permanently

*-r* : recursively

*-f* : force

### Sort command 
` It's used to sort or arrange lines of text in a particular order`
```bash
 SYNTAX : sort [option] [file]
sort filename : sort alphabetically
sort -r filename : sort in reverse
-n : sort numeric value
-nr : sorn numeric value in reverse order
-k : sort by particular column
 `eg` : rojina , prajina , roshya
sort -k1 name.txt 
output : prajina , rojina , roshya
-u : sort unique word
-f : caseinsensitive means ignore upper or lowercase
-h : sort human-readable numeric
-M : sort by month
-c : check if file is already sorted
-o : store sorted file `eg` : sort file.txt -o file.txt


