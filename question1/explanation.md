command: cd ~
i used this command to move from windows system folder to my linux home directory and after this my prompt changed to /home/rahar.

command: pwd
this command showed my present working directory and i observed the output as /home/rahar.

command: ls
this command listed files in my home directory and at this time no files were present so nothing was shown.

command: whoami
this command showed the currently logged in user and i observed my username as rahar.

command: groups
this command displayed all groups of my user account and i observed that my user rahar belongs to adm cdrom sudo dip plugdev and users group.

command: pwd
this command again confirmed my current directory and it showed /home/rahar.

command: ls -l
this command listed files in long format and i observed total 0 because there were no files in the directory.

command: echo "linux user environment verified" > user_info.txt
this command created a file named user_info.txt successfully in my home directory.

command: ls -l
after creating the file this command showed user_info.txt with size 32 bytes and owner rahar.

command: wc -c user_info.txt
this command counted total characters in the file and i observed the output as 32 characters.

command: man mkdir
this command opened the manual page of mkdir command and i learned about its usage and options.

command: ls ~ | sort
this command listed files in home directory in sorted order and user_info.txt was displayed.

command: grep "admin" log.txt
this command returned error because log.txt file was not present at that time.

command: echo -e "user login\nadmin access granted\nnormal user\nadmin logged out" > log.txt
this command created a log.txt file and wrote sample log entries inside it.

command: grep "admin" log.txt
this command searched the word admin and displayed only matching lines like admin access granted and admin logged out.

command: uname -r
this command showed the linux kernel version and i observed it as 6.6.87.2-microsoft-standard-wsl2.

command: ping -c 4 www.google.com
this command checked network connectivity and i observed 4 packets sent and received with 0 percent packet loss.

command: uptime
this command showed system running time and i observed the system was up for around 40 minutes with 1 user logged in.
