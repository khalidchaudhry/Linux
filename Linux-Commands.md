Linux Commands
============
### . refers to the current directory
### . . refers to the parent directory
 
_A list of my commonly used Linux commands_
### Navigation
| Command | Description |
| ------- | ----------- |
| `cd ..` |  move to parent directory of current directory
| `cd /` | move to the root directory
| `cd -` | move to the previous working directory
### list files and directories
| Command | Description |
| ------- | ----------- |
| `pwd` | print working/current directory |
| `ls` |  list files/directories(aka folders) in the current directory|
| `ls /` |  list files/directories(aka folders) of the root directory|
| `ls ~` |  list files/directories(aka folders) of the user home directory|
| `ls ..` |  list files/directories(aka folders) of the current parent directory|
### Create soft and hard links
| Command | Description |
| ------- | ----------- |
| `ls -i` |shows the i-node number of files/directories in the current directory|
| `ls -i /` |shows the i-node number of files/directories in the root directory|
| `ls -s <original file/directory> <soft file/directory>` | Create soft link file/directory for original file/directory.|
| `ls <original file> <hard file>` | Create hard link for file for original file.**Not supported for directories**|



