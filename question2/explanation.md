command: mkdir ~/documents
this command created a new directory named documents inside my home directory and since no error message appeared i understood that the directory was created successfully.

command: cd ~/documents
this command moved me inside the documents directory and i observed that the terminal prompt changed from home directory to ~/documents.

command: touch plan.txt
this command created an empty file named plan.txt in the documents directory and the file was ready to store content.

command: echo "this is my project file" > plan.txt
this command wrote the given text inside plan.txt and i observed that the file now contained the project related text.

command: ls -l plan.txt
this command displayed the file details and i observed that plan.txt is owned by user rahar with size 24 bytes and correct permissions.

command: cp plan.txt plan_copy.txt
this command created an exact copy of plan.txt named plan_copy.txt and both files existed in the same directory.

command: cd ~
this command moved me back to the home directory and the prompt again showed that i was working in /home/rahar.

command: mv documents project_documents
this command renamed the documents directory to project_documents and i observed that the folder name was updated successfully.

command: mkdir ~/project_documents/archive
this command created a new subdirectory named archive inside project_documents for storing copied files.

command: mv ~/project_documents/plan_copy.txt ~/project_documents/archive/
this command moved plan_copy.txt into the archive folder and the file was no longer visible in the main project_documents directory.

command: ls -R ~/project_documents
this command showed the complete directory structure and i observed plan.txt in project_documents and plan_copy.txt inside the archive folder.

command: realpath ~/project_documents/archive/plan_copy.txt
this command displayed the full absolute path of plan_copy.txt which confirmed its exact final location in the system.
