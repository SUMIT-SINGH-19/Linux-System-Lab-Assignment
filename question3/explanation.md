command: echo "this is sample data file" > sample_data.txt
i used this command to create a file named sample_data.txt and write text inside it, and the file was created successfully without any error.

command: ln sample_data.txt sample_hard.txt
this command created a hard link named sample_hard.txt and i understood that both files point to the same data because they share the same inode.

command: ln -s sample_data.txt sample_soft.txt
this command created a symbolic link which points to the original file sample_data.txt and works like a shortcut.

command: ls -li sample_data.txt sample_hard.txt sample_soft.txt
this command showed the inode numbers and i observed that sample_data.txt and sample_hard.txt had the same inode while sample_soft.txt had a different inode.

command: stat sample_data.txt
this command showed detailed file information and i observed the inode number and link count as 2 which confirmed hard link creation.

command: du -sh ~
this command showed the disk usage of my home directory and i observed the total size as 52k.

command: ls -lh ~
this command listed all files with their sizes and i observed that sample_data.txt and sample_hard.txt both had size 25 bytes.

command: rm sample_soft.txt
this command deleted the symbolic link sample_soft.txt successfully and no error was shown.

command: cat sample_data.txt
this command displayed the content of sample_data.txt and confirmed that the original file was not deleted.

command: df -h
this command displayed disk usage details of all mounted filesystems including total size and available space.
