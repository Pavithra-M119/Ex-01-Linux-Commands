# Ex-01-Linux-Commands


## Aim:

To study the execution of various Linux operating system commands.

## Linux:

Linux is an open-source operating system. The kernel is the heart of Linux OS which
 
helps the communication between hardware and software. The main advantage of Linux was that programmers can use Linux kernel to design their own custom OS.

Linux Commands:
All basic and advanced tasks can be done by executing commands. The commands are executed on Linux terminal. Linux commands are case sensitive.


## Commands:

### 1)	ls Command

The ls command is used to display a list of content of a directory.

 Syntax: ls
![image](https://github.com/Pavithra-M119/Ex-01-Linux-Commands/assets/119229774/df6b99d9-e5de-4f66-a336-1882139b8b23)


### 2)	pwd Command

The pwd command is used to display the location of the current working directory.

Syntax: pwd
![image](https://github.com/Pavithra-M119/Ex-01-Linux-Commands/assets/119229774/ae47a35b-7c32-4e38-9210-0dd139467f47)

 
### 3)	mkdir Command

The mkdir command is used to create a new directory under any directory.

Syntax: mkdir <directory name>
![image](https://github.com/Pavithra-M119/Ex-01-Linux-Commands/assets/119229774/1770f50a-2134-40e2-9292-e29a9b6e6962)


### 4)	rmdir Command

The rmdir command is used to delete a directory.

Syntax: rmdir <directory name>
![image](https://github.com/Pavithra-M119/Ex-01-Linux-Commands/assets/119229774/4dd32e69-bf5c-44cc-8158-73c680d1f690)


### 5)	cd Command

The cd command is used to change the current directory.

Syntax: cd <directory name>
![image](https://github.com/Pavithra-M119/Ex-01-Linux-Commands/assets/119229774/badbf7a4-df32-47fc-81e9-11b6bea5090e)


### 6)	cat Command

The cat command is a multi-purpose utility in the Linux system. It can be used to create a file, display content of the file, copy the content of one file to another file, and more.

Syntax: cat [OPTION]... [FILE]..
![image](https://github.com/Pavithra-M119/Ex-01-Linux-Commands/assets/119229774/11acd5a1-f2a5-4ede-a00a-78ec60c994b8)

 
### 7)	cp Command

The cp command is used to copy a file or directory.

Syntax: cp <existing file name> <new file name>
![image](https://github.com/Pavithra-M119/Ex-01-Linux-Commands/assets/119229774/a783e4fb-3aa2-4d5d-bafb-04b2b3b6a1c2)



### 8)	gedit Command

The gedit is a general-purpose text editor. It can be used to create and edit all kinds of text files.

Syntax: gedit file_name
![image](https://github.com/Pavithra-M119/Ex-01-Linux-Commands/assets/119229774/b98290c3-584b-49f4-b98d-2b27d54b02e1)


### 9)	su Command

The su command provides administrative access to another user. In other words, it allows access of the Linux shell to another user.

Syntax: su <user name>
![image](https://github.com/Pavithra-M119/Ex-01-Linux-Commands/assets/119229774/8b886fa8-ed3a-450e-b5ac-e9a0fdbc33dd)


### 10)	mv Command

The mv command is used to move a file or a directory form one location to another location.

Syntax: mv <file name> <directory path>
![image](https://github.com/Pavithra-M119/Ex-01-Linux-Commands/assets/119229774/75db2f52-3a64-4e45-9f1e-df060c1457a5)

 
## 11)	rename Command

The rename command is used to rename files. It is useful for renaming a large group of files.

Syntax: rename 's/old-name/new-name/' files
![image](https://github.com/Pavithra-M119/Ex-01-Linux-Commands/assets/119229774/5fe1c66f-d091-4bb2-b375-09da06b4063a)


### 12)	head Command

The head command is used to display the content of a file. It displays the first 10 lines of a file.

Syntax: head <file name>
![image](https://github.com/Pavithra-M119/Ex-01-Linux-Commands/assets/119229774/cb2bcebc-31b8-44e7-b776-d6b83b5e4fe5)


### 13)	tail Command

The tail command is similar to the head command. The difference between both commands is that it displays the last ten lines of the file content. It is useful for reading the error message.

Syntax: tail <file name>
![image](https://github.com/Pavithra-M119/Ex-01-Linux-Commands/assets/119229774/28283ede-27e7-4953-b0e3-382970db9cad)

 
### 14)	id Command

The id command is used to display the user ID (UID) and group ID (GID).

Syntax: id
![image](https://github.com/Pavithra-M119/Ex-01-Linux-Commands/assets/119229774/f06d6608-540c-417d-a478-95dff837f33a)


### 15)	grep Command

The grep is the most powerful and used filter in a Linux system. The 'grep' stands for "global regular expression print." It is useful for searching the content from a file. Generally, it is used with the pipe.

Syntax: command | grep <search word>
![image](https://github.com/Pavithra-M119/Ex-01-Linux-Commands/assets/119229774/e414b33e-6e38-46b8-8b37-7bb289641fe1)


### 16)	tr Command

The tr command is used to translate the file content like from lower case to upper case.

Syntax: command | tr <'old'> <'new'>
![image](https://github.com/Pavithra-M119/Ex-01-Linux-Commands/assets/119229774/ca570ea4-aeb0-498e-a72e-db0477ddf3d6)

### 17)	chmod Command

The chmod command is used to change the access mode of a file (i.e., read, write or execute)

Syntax: chmod<options><permissions><file_name>

### 18)	tar Command

The tar command is used for creating Archieve and extracting the archieve files.

Syntax: tar[options][archieve-file] [file to be archieved]
$ tar xvzf file.tar *.c
 
### 19)	chown Command

The chown command is used to change ownership.

Syntax: chown owner_name file_name
![image](https://github.com/Pavithra-M119/Ex-01-Linux-Commands/assets/119229774/5821b4d3-3222-4036-9e9a-d0703a79b3d0)

### 20)	make Command

The make command is used for building and maintaining group of program.

Syntax: make [-f makefile][options]…….[targets]….
![image](https://github.com/Pavithra-M119/Ex-01-Linux-Commands/assets/119229774/ce6b2acc-89ce-4335-b192-fcbc962b878e)


### 21)	ifconfig Command

The ifconfig command is used to configure kernel-resident network interface.

Syntax: ifconfig[options][interface]
![image](https://github.com/Pavithra-M119/Ex-01-Linux-Commands/assets/119229774/f71c7b62-a03a-470c-816e-2e866b1d310b)

### 22)	chmod 777 Command

The chmod 777 command gives read, write and execute permission to the owner, group and public.

Syntax: chmod 777 file_name
$chmod -R 777 /path/to/file/or/folder
 
### 23)	host Command

The host command is used to display the IP address for a given domain name and vice versa. It performs the DNS lookups for the DNS Query.

Syntax: host <domain name> or <ip address>
![image](https://github.com/Pavithra-M119/Ex-01-Linux-Commands/assets/119229774/56452b82-9656-4f6f-90d4-3d531b8eb6c2)


### 24)	gzip Command

The gzip command is used to truncate the file size. It is a compressing tool. It replaces the original file by the compressed file having '.gz' extension.

Syntax: gzip <file1> <file2> <file3>..
![image](https://github.com/Pavithra-M119/Ex-01-Linux-Commands/assets/119229774/936303f0-f340-412e-91bd-c3fe93d68997)


### 25)	sort Command

The sort command is used to sort files in alphabetical order.

Syntax:sort <file name>
![image](https://github.com/Pavithra-M119/Ex-01-Linux-Commands/assets/119229774/fefa6869-19d1-4be3-a1b1-181aadbf5d79)

 
### 26)	cal Command

The cal command is used to display the current month's calendar with the current date highlighted.

Syntax: cal
![image](https://github.com/Pavithra-M119/Ex-01-Linux-Commands/assets/119229774/530a0b2c-4e47-47aa-93f3-e5456daa759d)


### 27)	clear Command

Linux clear command is used to clear the terminal screen.

Syntax: clear
![image](https://github.com/Pavithra-M119/Ex-01-Linux-Commands/assets/119229774/5bdfa439-3ee8-474d-a661-71d04bb2af08)


### 28)	mail Command

The mail command is used to send emails from the command line.

Syntax: mail -s "Subject" <recipient address>
![image](https://github.com/Pavithra-M119/Ex-01-Linux-Commands/assets/119229774/ec52df25-4427-434d-9266-261d9597dab6)

 
### 29)	df Command

The df command is used to display the disk space used in the file system. It displays the output as in the number of used blocks, available blocks, and the mounted directory.

Syntax: df
![image](https://github.com/Pavithra-M119/Ex-01-Linux-Commands/assets/119229774/71eea654-4564-4ea9-a776-15f0b03b71de)

### 30)	find Command

The find command is used to find a particular file within a directory.

Syntax: find.-name”*.pdf”





















## Result:

Thus, the execution of various Linux commands is executed successfully using Ubuntu OS.
