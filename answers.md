## Exrcise 1:
## home directory is `pwd` 
## folders in home directory: `ls` 
## navigating back `cd ~`

## Exercise 2: The command will take 3 levels above your home directory. The cd part wil take you to the home directory. The remaining part will move you 3 levels about the current directory.


## Exercise 3: a stands for "all" (it also displays hidden files or dot files).l stands for "long" (offers detailed information about each file and directory in a long listing format. This includes file permissions, number of links, owner name, group name, size, date and time of last modification, and the filename itself).

## Exercise 4: 
## ‛touch myfile.txt‛ ‛stat myfile.txt‛
##‛stat myfile.txt‛ provides detailed information about the file. Here’s the paraphrased explanation for each part of the output: ‛stat myfile.txt‛ shows the name of the file. ‛Size: 0‛ indicates that the size of the file is 0 bytes. ‛Blocks: 0‛ indicates that the file occupies 0 blocks on the disk. ‛IO Block: 65536‛ specifies that the size of each block is 65536 bytes. ‛regular empty file‛ indicates the file is a regular file and currently empty. ‛Device: d0ab7935h/3500898613d‛ shows the unique device number where the file is stored. ‛Inode: 101612466592571689‛ provides the inode number, which is a unique identifier for the file within the file system. ‛Links: 1‛ indicates that there is one link (or reference) to the file. ‛Access: (0644/-rw-r--r--)‛ shows the file's access permissions in both octal and symbolic notation. The file is readable and writable by the owner, and readable by the group and others. ‛Uid: (1754655/semiyari)‛ displays the user ID and username of the file's owner. ‛Gid: (1049089/UNKNOWN)‛ shows the group ID and the group name (UNKNOWN if it can't be determined) to which the file belongs. ‛Access: 2024-07-08 17:36:31.153073900 -0400‛ indicates the last time the file was accessed. ‛Modify: 2024-07-08 17:36:31.153073900 -0400‛ shows the last time the file was modified. ‛Change: 2024-07-08 17:36:31.152213300 -0400‛ indicates the last time the file’s metadata or status was changed. ‛Birth: 2024-07-08 17:36:31.152213300 -0400‛ provides the time the file was created, if the file system supports this feature. 
## Exercise 5: The `ls -l` command will provide a detailed listing of the files in the directory.
## Exercise 6: `echo "this line is my first line" > myfile.txt type `cat myfile.txt`
## Exercise 7: `touch myfile.tx` `ls -l myfile.txt`
