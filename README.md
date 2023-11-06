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
![image](https://github.com/DrMalathiSaravanan/Ex-01-Linux-Commands/assets/119229774/de5af182-0b1b-42d2-b62e-c69f10d39626)



### 2)	pwd Command

The pwd command is used to display the location of the current working directory.

Syntax: pwd
![image](https://github.com/DrMalathiSaravanan/Ex-01-Linux-Commands/assets/119229774/97ec57b5-abaf-4bf3-af99-942adcabce68)

 
### 3)	mkdir Command

The mkdir command is used to create a new directory under any directory.

Syntax: mkdir <directory name>
![image](https://github.com/DrMalathiSaravanan/Ex-01-Linux-Commands/assets/119229774/8485a6c4-28ac-4e3e-ae35-402c421f41f7)


### 4)	rmdir Command

The rmdir command is used to delete a directory.

Syntax: rmdir <directory name>


### 5)	cd Command

The cd command is used to change the current directory.

Syntax: cd <directory name>
![image](https://github.com/DrMalathiSaravanan/Ex-01-Linux-Commands/assets/119229774/9cb8d210-ef8b-4b04-9257-3c1c8507a19e)


### 6)	cat Command

The cat command is a multi-purpose utility in the Linux system. It can be used to create a file, display content of the file, copy the content of one file to another file, and more.

Syntax: cat [OPTION]... [FILE]..
![image](https://github.com/DrMalathiSaravanan/Ex-01-Linux-Commands/assets/119229774/ff1a8406-54bf-46fc-b189-302fb96e2709)

 
### 7)	cp Command

The cp command is used to copy a file or directory.

Syntax: cp <existing file name> <new file name>
![image](https://github.com/DrMalathiSaravanan/Ex-01-Linux-Commands/assets/119229774/86e7316b-308c-4c5e-a9bc-6c5f7e5f1fdd)



### 8)	gedit Command

The gedit is a general-purpose text editor. It can be used to create and edit all kinds of text files.

Syntax: gedit file_name
![image](https://github.com/DrMalathiSaravanan/Ex-01-Linux-Commands/assets/119229774/a5595b3b-36aa-4799-a4e3-55dd322a74bf)


### 9)	su Command

The su command provides administrative access to another user. In other words, it allows access of the Linux shell to another user.

Syntax: su <user name>
![image](https://github.com/DrMalathiSaravanan/Ex-01-Linux-Commands/assets/119229774/79a641f8-16d2-4e60-acf7-b6ea050c6ec6)


### 10)	mv Command

The mv command is used to move a file or a directory form one location to another location.

Syntax: mv <file name> <directory path>

 
## 11)	rename Command

The rename command is used to rename files. It is useful for renaming a large group of files.

Syntax: rename 's/old-name/new-name/' files
![image](https://github.com/DrMalathiSaravanan/Ex-01-Linux-Commands/assets/119229774/4ebe65a7-b38d-41d1-8dc0-468dde04be24)


### 12)	head Command

The head command is used to display the content of a file. It displays the first 10 lines of a file.

Syntax: head <file name>
![image](https://github.com/DrMalathiSaravanan/Ex-01-Linux-Commands/assets/119229774/ef8c1662-5c9e-41cb-8eca-0916a9839271)


### 13)	tail Command

The tail command is similar to the head command. The difference between both commands is that it displays the last ten lines of the file content. It is useful for reading the error message.

Syntax: tail <file name>
![image](https://github.com/DrMalathiSaravanan/Ex-01-Linux-Commands/assets/119229774/e9180c16-3f7b-4d9c-9e3d-d85192b2a1b8)

 
### 14)	id Command

The id command is used to display the user ID (UID) and group ID (GID).

Syntax: id
![image](https://github.com/DrMalathiSaravanan/Ex-01-Linux-Commands/assets/119229774/746b6c55-db86-4f60-a4c0-7a0da819da2a)


### 15)	grep Command

The grep is the most powerful and used filter in a Linux system. The 'grep' stands for "global regular expression print." It is useful for searching the content from a file. Generally, it is used with the pipe.

Syntax: command | grep <search word>
![image](https://github.com/DrMalathiSaravanan/Ex-01-Linux-Commands/assets/119229774/a72c28e3-0d1f-4b22-9299-41d1461b8734)


### 16)	tr Command

The tr command is used to translate the file content like from lower case to upper case.

Syntax: command | tr <'old'> <'new'>

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

### 20)	make Command

The make command is used for building and maintaining group of program.

Syntax: make [-f makefile][options]…….[targets]….


### 21)	ifconfig Command

The ifconfig command is used to configure kernel-resident network interface.

Syntax: ifconfig[options][interface]

### 22)	chmod 777 Command

The chmod 777 command gives read, write and execute permission to the owner, group and public.

Syntax: chmod 777 file_name
$chmod -R 777 /path/to/file/or/folder
 
### 23)	host Command

The host command is used to display the IP address for a given domain name and vice versa. It performs the DNS lookups for the DNS Query.

Syntax: host <domain name> or <ip address>


### 24)	gzip Command

The gzip command is used to truncate the file size. It is a compressing tool. It replaces the original file by the compressed file having '.gz' extension.

Syntax: gzip <file1> <file2> <file3>..


### 25)	sort Command

The sort command is used to sort files in alphabetical order.

Syntax:sort <file name>

 
### 26)	cal Command

The cal command is used to display the current month's calendar with the current date highlighted.

Syntax: cal


### 27)	clear Command

Linux clear command is used to clear the terminal screen.

Syntax: clear


### 28)	mail Command

The mail command is used to send emails from the command line.

Syntax: mail -s "Subject" <recipient address>

 
### 29)	df Command

The df command is used to display the disk space used in the file system. It displays the output as in the number of used blocks, available blocks, and the mounted directory.

Syntax: df
![Uploading image.png…]()

### 30)	find Command

The find command is used to find a particular file within a directory.

Syntax: find.-name”*.pdf”





















## Result:

Thus, the execution of various Linux commands is executed successfully using Ubuntu OS.
