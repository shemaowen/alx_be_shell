# Script Descriptions
This repository contains several Bash scripts that perform various tasks related to file management and user permissions.


## Script 1: Switch User to Betty
### Description: 
This script switches the current user to the user betty.
### Command Used: 
su betty
### Usage: 
Ensure that the user betty exists on the system before running this script.

## Script 2: Who am I
### Description: 
This script prints the effective username of the current user.
### Command Used: 
whoami
### Usage:
Simply execute the script to see the current user's username printed to the terminal.

## Script 3: Empty!
### Description: 
This script creates an empty file named hello.
### Command Used: 
touch hello
### Usage: 
Run the script to create an empty file named hello in the current working directory.

## Script 4: Add Execute Permission to Owner
### Description: 
This script adds execute (x) permission to the owner of the file hello.
### Command Used: 
chmod +x hello
### Usage: 
Ensure that the file hello exists in the working directory. This script grants execute permission to the owner of hello.

## Script 5: Modify File Permissions
### Description: 
This script sets specific permissions for the file hello:

Owner (julien): Read and execute (r-x)
Group (julien): Read and execute (r-x)
Others: Read only (r--)

### Command Used: 
chmod 554 hello
### Usage: 
Make sure hello exists in the current directory. This script sets the permissions as specified for hello.

## Script 6: Set Custom File Mode
### Description: 
This script sets the file mode of hello to -rwxr-x-wx 1 julien julien.
### Command Used: 
chmod 753 hello
### Usage: 
Ensure hello is present in the working directory. This script applies the custom file mode -rwxr-x-wx to hello.

<br />
<br />


> [!NOTE]
> Each script in this repository is designed to perform a specific file management task or demonstrate setting file permissions. Please ensure appropriate permissions and file existence before executing these scripts.
