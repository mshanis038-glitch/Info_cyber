# LINUX COMMANDS
# 1) Package Management (Debian-based)

| Command | Description | Example |
|----------|-------------|---------|
|'apt update'|Update repo info | 'sudo apt update' |
|'apt upgrade'| Upgrade packages |'sudo apt upgrade'|
|'apt install' | Install a package|'sudo apt install nmap'|
|'apt remove'| Remove a packageI |'sudo apt remove apache2'|


## 2) File & Directory Commands
|Command |Description              |Example                    |
|--------|-------------------------|---------------------------|
|'pwd'   |Show current directory   |'pwd'                      |
|'ls'    |List files/directories   |'ls'                       |
|'ls -1' |Detailed listing         |'ls -1'                    |
|'ls -a' |Show hidden files        |'ls -a'                    |
|'cd'    |Change directories       |'cd /etc'                  |
|'cd ..' |Go up oone level         |'cd ..'                    |
|'cd ~'  |Go to home directory     |'cd ~'                     |
|'cd -'  |Go to previous directory |'cd -'                     |
|'mkdir' |Create directory         |'mkdir testdir'            |
|'rmdir' |Remove empty directory   |'rmdir testdir'            |
|'rm'    |Remove file/directories  |'rm file.txt', 'rm -r dir/'|
|'touch' |Creat empty files        |'touch file.txt'           |
|'cp'    |Copy file/directories    |'cp file1.txt file2.txt'   |
|'mv'    |Move/rename file         |'mv file1.txt file2.txt'   |
|'find'  |Search for files         |'find . name "*.sh"'       |

## 3) File content commands
|Command           |Description                  |Example                         |
|------------------|-----------------------------|--------------------------------|
|'cat'             |View file content            |'cat file.txt'                  |
|'more', 'less'    |View file with scroll        |'more file.txt', 'less file.txt'|
|'head'            |View first 10 lines          |'head file.txt'                 |
|'tail'            |View last 10 lines           |'tail file.txt'                 |
|'wc'              |Word/line count              |'wc -1 file.txt'                |
|'cut'             |Extract column               |'cut -d', '-f file.csv'         |
|'sort'            |Sort file lines              |'sort file.txt'                 |
|'uniq'            |Removes duplicates           |'uniq file.txt'                 |
|'diff'            |Show difference between files|'diff file.txt'                 |

## 4) User & Permissions

| Command | Description | Example |
|----------|--------------|----------|
| whoami | Show current user | whoami |
| id | Show user and group IDs | id |
| chmod | Change file permissions | chmod 755 script.sh |
| chown | Change file owner and group | chown root:root file.txt |
| adduser | Add a new user | sudo adduser alice |
| passwd | Change user password | passwd alice |
| su | Switch user | su - |
| sudo | Run command as superuser | sudo apt update |

## 5) Networking

| Command | Description | Example |
|----------|--------------|----------|
| ping | Test network connectivity | ping google.com |
| ifconfig / ip a | View network interfaces and IP addresses | ip a |
| netstat -tuln | View open ports  | netstat -tuln |
| curl | Fetch data from a URL | curl http://example.com |
| wget | Download files from the internet | wget http://file.com/file.txt |

## 6) File Compression & Archiving

| Command | Description | Example |
|----------|--------------|----------|
| tar -cf | Archive multiple files into a .tar file | tar -cf archive.tar file1 file2 |
| tar -xvf | Extract files from a .tar archive | tar -xvf archive.tar |
| tar -czvf | Create a compressed .tar.gz archive | tar -czvf archive.tar.gz dir/ |
| gzip | Compress a file (creates .gz) | gzip file.txt |
| gunzip | Decompress a .gz file | gunzip file.txt.gz |
| zip | Compress files into a .zip archive | zip archive.zip file1 file2 |
| unzip | Extract files from a .zip archive | unzip archive.zip |
