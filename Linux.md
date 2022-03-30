# Belajar Command Linux v1
---
### Table Of Contents
- Linux Command
- System Managements and Information
  - System Information
  - System shutdown
  - Add a new kernel module
- File Commands
  - List Files
  - Remove a File
  - Show the File
  - Encrypt a File
  - Decrypt a File
  - Sort File Contents
  - File Permission
- Bash Scripting 
---
#### Linux Command
A Linux command is a program or utility that runs on the command line. A command line is an interface that accepts lines of text and processes them into instructions for your computer.
#### System Managements and Information
 - System Information
   - Show system information:
    1. Show system information:
   ```
   uname -r
   ```
    2. See kernel release information:
   ```
   uname -a
   ```
    2. Display how long the system has been running, including load average:
   ```
   uptime
   ```
    3. See system hostname:
   ```
   hostname
   ```
    4. Show the IP address of the system:
   ```
   hostname -i
   ```
    5. List system reboot history:
   ```
   last reboot
   ```
    6. See current time and date:
   ```
   date
   ```
    7. Show current calendar (month and day):
   ```
   cal
   ```
    8.  See which user you are using:
   ```
   whoami
   ```
    9. Show information about a particular user:
   ```
   finger [username]
   ```
    10. See free and used space on mounted systems:
   ```
   df -h
   ```
- System shutdown
   - System shutdown
   1. Schedule a system shutdown:
   ```
   shutdown [hh:mm]
   ```
   2. Shut Down the system immediately:
   ```
   shutdown now
   ```
- Add a new kernel module
   - Add a new kernel module
   ```
   modprobe [module-name]
   ```
#### File Commands
- List Files
  - List files in the directory:
  ```
  ls
  ```  
  - List all files (shows hidden files):
  ```
  ls -a 
  ``` 
  - List files and sort by date and time:
  ```
  ls -t
  ``` 
  - List files with subdirectories
  ```
  ls *
  ``` 
- Remove  a File
  - Remove a file:
  ```
  rm [file_name]
  ```  
  - Remove a directory recursively:
  ```
  rm -r [directory_name]
  ``` 
  - Recursively remove a directory without requiring confirmation:
  ```
  rm -rf [directory_name]
  ``` 
- Show the File
  - Show the contents of a file:
  ```
  more [file_name]
  ```
  - Show the last 10 lines of a file:
  ```
  tail [file_name]
  ```
  - Display the first 10 lines of a file:
  ```
  head [file_name]
  ```
  - Show the number of words, lines, and bytes in a file:
  ```
  wc
  ```     
- Encrypt a File
  ```
  gpg -c [file_name]
  ``` 
- Decrypt a File
  ```
  gpg [file_name.gpg]
  ``` 
- Sort File Contents
  - Sort file contents and print the result in standard output:
  ```
  sort [options] filename
  ```  
- File Permission
  - Assign read, write, and execute permission to everyone:
  ```
  chmod 777 [file_name]
  ``` 
  - Give read, write, and execute permission to owner, and read and execute permission to group and others:
  ```
  chmod 755 [file_name]
  ``` 
  - Assign full permission to owner, and read and write permission to group and others:
  ```
  chmod 766 [file_name]
  ``` 
  - Assign full permission to owner, and read and write permission to group and others:
  ```
  chown [user] [file_name]
  ``` 
  - Change the ownership of a file:
  ```
  chown [user] [file_name]
  ``` 
  - Change the owner and group ownership of a file:
  ```
  chown [user]:[group] [file_name]
  ```  










