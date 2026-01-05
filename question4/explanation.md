command: uptime
this command showed how long the system has been running and i observed the uptime duration along with number of logged-in users and load average.

command: ps -u $USER
this command listed all the processes running under my user account and showed the process ids and command names.

command: top -u $USER
this command displayed real time cpu and memory usage and i observed that no process was using high cpu at that moment.

command: sleep 300 &
this command started a process in the background and the system returned a job id confirming it was running.

command: jobs
this command showed the list of background jobs and confirmed that the sleep process was running.

command: ps -u $USER
this command was used again to verify running processes and i observed the sleep process in the process list.

command: renice 10 -p <pid>
this command was used to change the priority of a running process and i observed the priority value changed successfully for the selected process.

command: free -h
this command displayed memory usage in human readable format and showed total used and free memory of the system.

command: df -h ~
this command showed disk space usage of the filesystem where my home directory is located and confirmed sufficient free space.

command: echo $SHELL
this command displayed the name of the shell currently in use and i observed it was /bin/bash.

command: uname -a > system_report.txt
this command saved system information like kernel version and architecture into a file named system_report.txt.

command: cat system_report.txt
this command displayed the content of system_report.txt and confirmed that the system information was written correctly.

command: sudo apt install ncdu
this command checked and installed ncdu tool and i observed that ncdu was already installed on the system.

command: ncdu ~
this command opened an interactive disk usage view and showed which folders were using disk space inside the home directory.
