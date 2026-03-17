# linux-basic-assignment-sanjay
1.  pwd Displays the current working directory path 
3.  ls Lists files and directories in the current location.
4.  cd Changes the current directory.
5.  mkdir Creates a new directory 
6.  rm -rf Deletes files/directories forcefully and recursively
7.  ps -ef Displays all running processes in full format
8.  top Shows real-time system processes and resource usage
9.  df -h Displays disk space usage in human-readable format
10.  history Shows previously executed commands
11. uptime Shows how long the system has been running and load average.

1.  Create a directory called project-files     mkdir project-files
2.  Navigate into the project-files directory     cd project-files
3.  Create a file called notes.txt using vi         vi notes.txt
4.  Display the contents of notes.txt                 cat notes.txt
5.  Copy notes.txt to backup.txt                      cp notes.txt backup.txt
6.  Show the first 100 lines of a file called logs.txt    head -n 100 logs.txt
7.  Show the last 100 lines of logs.txt                    tail -n 100 logs.txt
8.  Check the disk storage usage of the server                  df -h
9.  Check the running processes in the system                  ps -ef
10. Delete a file called temp.txt                             rm temp.txt




1.  What is the difference between > and >> in Linux?     > Overwrites the file (old content is deleted) and → Appends data to the file (keeps old content) 
2.  What is the purpose of the kill -9 command? The process is stopped immediately (no cleanup or saving)
3.  What is the difference between rm and rmdir?  Deletes files and directories (with -r for folders).
4.  What information does the netstat -tulpn command provide? Shows active network connections and listening ports

Displays:

Protocol (TCP/UDP)

Port numbers

Process ID (PID)

Program name
5.  What is the purpose of the ping command?  Tests network connectivity between your system and another host.

Measures response time (latency) and checks if the host is reachable.
