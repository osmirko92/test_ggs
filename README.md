##  Basic work with files

- Create directory test1

```console
mkdir test
```

- Create file test1.txt inside the test1 directory.
```console
touch test.txt
```

-   Create copy of folder test1 with name test2.  
```console
cp -R /home/osmirko/Desktop/GIT/test_ggs/test /home/osmirko/Desktop/GIT/test_ggs/test2
```
-    Delete file test1.txt inside test2 directory.
```console
rm test1.txt
```
-    Rename test2 folder into directory_without_file
```console
mv /home/osmirko/Desktop/GIT/test_ggs/test2 /home/osmirko/Desktop/GIT/test_ggs/directory__without_file
```
-    Insert 'test1' text into test1/test1.txt file.
```console
echo test1 > /home/osmirko/Desktop/GIT/test_ggs/test1/test1.txt 
```
-    print the text from the test1/test1.txt file.
```console
cat test1.txt
```
-    Insert 'test2' into the end of test1/test1.txt file.
```console
echo test2 >> /home/osmirko/Desktop/GIT/test_ggs/test1/test1.txt
```
-    print the text from the test1/test1.txt file.
```console
cat test1.txt
```
- check the size of test1 directory
```console
du test1
```
## Permissions

-   Create test directory and block access for all to it.
```console
sudo chmod -R 000 test
```
-   Try to remove that directory.
```console
rm -R test
rm: descend into write-protected directory 'test'? y
rm: remove write-protected directory 'test'? y
```
-    Create simple script which prints current date. Try to execute it.
```console
vim script1.sh
   #! /bin/sh.
   date

bash script1.sh
```

## Log checking

-  Count lines in the file test.txt.
```console
```
- Show last 3 lines from the test.txt file. 


-  Hom many uniq IP addresses accessed the website ? 


-  IP address with most requests.


-  Top 3 IP addresses by amount of POST requests.


-  Which IP addresses received 403 error ? 


- Task with * . Write script to show which pages Google checked from the website 

## Replace

Replace IP address with most requests on 127.0.0.1 in test.txt file 
