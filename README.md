# First step into ASW

Create machine on AWS.

- Use SSH key that was made during the creation of the machine to connect you pc to your AWS Virtual Machine.
- You'll need to use that ssh key to ssh into your virtual Machine
    $ ssh -i <repo where your ssh key is> ubuntu@<public DNS>

- Move a folder from your local machine to your VM on AWS. Ensure you are in the right folder on your local machine before attempting to move the folder
    $ scp -i <repo where your ssh key is> -r <name of folder you want to move> ubuntu@<public DNS>

- Move a specific file from your local machine to your VM.
    $ scp -i <repo where your ssh key is> <name of file you want to move> ubuntu@<public DNS>

- In the case of using a windows machine for a linix machine. Use dos2unix to convert windows files to the linix files. If its not installed in your computer, just download it from the internet.

# DO NOT, I REPEAT DO NOT!!!!! PUSH ANY KEYS TO GITHUB OR CREDENTIALS FROM AWS OR ANY OTHER EXTERNAL SERVICES. IT CAN BE A MAJOUR SECURITY RISK! :fire:
