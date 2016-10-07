##Bash Script


```
man - open manual of a command
cd - enter a new directory
mkdir - make a directory in the current directory
man - open a manual of a command
echo - prints an argument
tail - reads the last x lines of a file
less - a way to navigate through a file, allows you to move backward to the file
grep - search function
  -i - remove case sensitivity
  -r - search recursively
  -w - search only whole words
  -c - print number of times found
  -n - prints line found on with phrase
  -v - prints invert match
sed - a stream editor that performs text transformation
history - command prints out na incremented command line history
```

### Get top rows of file
```
head -{number of rows} {filename}

eg.
head -2 file.txt
```

Copy files from your remote server to yoru localhost
```
scp -i {pem.file} {user}@{ip}{directory/filename} {LOCAL_HOST_DIR}
```

### Session
```
screen
screen -ls
killall screen
```

### Gzip
Extract file
`gzip -d file.gz`
Compress file
`gzip -c file.txt > file.txt.gzip`

### Free disk space
```
1. lsof | grep deleted
2. cd /proc/{pid}/fd
3. > {pid}
```

###kill process bound to port 80
`sudo fuser -k 80/tcp`

###kill running server in port 3000
``kill -9 $(lsof -i tcp:3000 -t)``

###GREP
Match multiple strings and output to a file

`grep '"FAILED".*2015-11-04.*2015-11-05.*2015-11-06' og_file.txt > new_file.txt`

###Split large files 
```
split --bytes {size} {filename}
eg.
split --bytes 100M filename
```

Trim logs
```
1. Join all .xml files
cat *.xml > {filename.xml}
2. Split file in smaller bytes
split --bytes 100M filename
``` 
