
## ## Internsctl - Linux Command Utility
**Version 1.0**

###### Introduction
*internsctl is a versatile Linux command utility that provides various functionalities related to CPU, memory, user management, and file information. This Bash script allows users to interact with the system and obtain valuable information through a set of commands and options.

Installation
Download the Script:

Download the internsctl script to your local machine. You can do this by copying the script content from the provided source and saving it to a file named internsctl.

Make it Executable:

Open a terminal and navigate to the directory where you saved the internsctl script. Run the following command to make it executable:

`chmod +x internsctl`
Install Dependencies (Optional):

If necessary, you can install any dependencies required by the script using the following command:


`./internsctl --install`

Usage

Basic Commands
Display CPU Information:
`./internsctl cpu getinfo`


Display Memory Information:
`./internsctl memory getinfo`

Create a New User:
`./internsctl user create <username>`


List All Regular Users:
./internsctl user list


List Users with sudo Permissions:
`./internsctl user list --sudo-only`


Get File Information:
`./internsctl file getinfo <file-name>`

Additional Commands

Get Specific File Information:

Size:
`./internsctl file getinfo --size <file-name>`

Permissions:
`./internsctl file getinfo --permissions <file-name>`

Owner:
`./internsctl file getinfo --owner <file-name>`


Last Modified Time:
`./internsctl file getinfo --last-modified <file-name>`


Show Help Information:
`./internsctl --help`

Show Version Information:
`./internsctl --version`

View Manual Page:
`./internsctl --manual`


Examples
Display CPU Information:
`./internsctl cpu getinfo`

Create a New User:
`./internsctl user create john_doe`

List All Regular Users:
`./internsctl user list`

List Users with sudo Permissions:
`./internsctl user list --sudo-only`

Get File Information:
`./internsctl file getinfo example.txt`

Get Specific File Information:
`./internsctl file getinfo --size example.txt`
`./internsctl file getinfo --permissions example.txt`
`./internsctl file getinfo --owner example.txt
./internsctl file getinfo --last-modified example.txt
`

Contributing
If you encounter issues or have suggestions for improvements, please create an issue or submit a pull request on the GitHub repository.

License
This project is licensed under the Xenon Statck Intern Project - see the LICENSE file for details.

*
