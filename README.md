## Basic work with files

### Create directory test1
```console
-mkdir test1
```

### Create file test1.txt inside the test1 directory.
```console
-cd test1/
-cat > test1.txt
```

###   Create copy of folder test1 with name test2.  
```console
-cp test1 test2
```

###    Delete file test1.txt inside test2 directory.
```console
-rm test2/test1.txt
```

###    Rename test2 folder into directory_without_file
```console
mv test2 directory_without_file
```

###    Insert 'test1' text into test1/test1.txt file.
```console
cat > test1/test1.txt
```

###    print the text from the test1/test1.txt file.
```console
cat test1/test1.txt
```

###    Insert 'test2' into the end of test1/test1.txt file.
```console
-cat >> test1/test1.txt
test2
```

###    print the text from the test1/test1.txt file.
```console
-cat test1/test1.txt
```

## Permissions

###   1. Create test directory and block access for all to it.

```console
mkdir test
chmod 000 test/
```

###   2. Try to remove that directory.

```console
rm -rf test/
```

###   3. Create simple script which prints current date. Try to execute it.

```console
#!/bin/bash

date 
```
