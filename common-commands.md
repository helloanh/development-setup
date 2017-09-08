# Common Everyday Commands
```bash
cp –a  
-	p same permission  
-	R recursive  
-	a both p and R  

mysqldump –h hostname –u username –p databasename > dumpfile.sql  
mysql –hdb –u username –p databasename < dumpfile.sql  

grep –Ril “findtext” /   
grep 'word' filename  
grep 'word' file1 file2 file3  
grep 'string1 string2'  filename  
cat otherfile | grep 'something'  
command | grep 'something'  
command option1 | grep 'data'  
grep --color 'data' fileName  
	-n option show each line where it matches in a file  

find /dir/ -name name*  
 Find files starting  with name in dir  

tar -cvf archive_name.tar directory_to_compress  
tar -xvf archive_name.tar.gz  
extract in different directory: tar -xvf archive_name.tar -C /tmp/extract_here/  
scp name:~/path/to/file  destination/in/you/local   
sudo service apache2 restart or stop/star or reload 

# aws
[glacer](http://docs.aws.amazon.com/cli/latest/reference/glacier/upload-archive.html)
#command 
aws glacier upload-archive --account-id numberer --vault-name anh-mac-os-bak --body fh-cs-coursework-jun-3-2017.tar.gz 
```


