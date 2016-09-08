###SHELL

#Get top rows of file
head -{number of rows} {filename}

eg.
head -2 myfile.csv

#Copy files from your remote server to yoru localhost
scp -i {pem.file} {user}@{ip}{directory/filename} {LOCAL_HOST_DIR}

#Session commands
screen
screen -ls
killall screen

#gunzip
gzip -d file.gz
gzip -c file.txt > file.txt.gzip

#Free disk space
1. lsof | grep deleted
2. cd /proc/{pid}/fd
3. > {pid}

#kill process bound to port 80
sudo fuser -k 80/tcp

#kill running server in port 3000
kill -9 $(lsof -i tcp:3000 -t)

#Match / GREP
  Match multiple strings and output to a file
  grep '"FAILED".*2015-11-04.*2015-11-05.*2015-11-06' oct_charges > oct_failed.csv

#Split large files
  split --bytes {size} {filename}
  eg.
  split --bytes 100M filename

  ***get voice logs
  1. Join all .xml files
    cat *.xml > {filename.xml}
    2. Split file in smaller bytes
      split --bytes 100M filename
      3. 
