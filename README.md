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

 ![image](https://github.com/user-attachments/assets/4dee40d8-658d-4ce1-ae9a-6ef34ba8921e)


### 2)	pwd Command

The pwd command is used to display the location of the current working directory.

Syntax: pwd

![image](https://github.com/user-attachments/assets/e2857c36-aab8-4608-872b-d81df07b7073)
 
### 3)	mkdir Command

The mkdir command is used to create a new directory under any directory.

Syntax: mkdir <directory name>

![image](https://github.com/user-attachments/assets/c8e24442-baee-4f72-bfe2-3565313b57e9)

### 4)	rmdir Command

The rmdir command is used to delete a directory.

Syntax: rmdir <directory name>

![image](https://github.com/user-attachments/assets/21bee100-3c89-4870-803a-ee1db914b37b)

### 5)	cd Command

The cd command is used to change the current directory.

Syntax: cd <directory name>

![image](https://github.com/user-attachments/assets/b62eeaef-0b5d-4732-ac35-b3e3d4a63dce)

### 6)	cat Command

The cat command is a multi-purpose utility in the Linux system. It can be used to create a file, display content of the file, copy the content of one file to another file, and more.

Syntax: cat [OPTION]... [FILE]..

![image](https://github.com/user-attachments/assets/2b8f3ee2-5292-43db-83c3-1323216485d5)


 
### 7)	cp Command

The cp command is used to copy a file or directory.

Syntax: cp <existing file name> <new file name>

![image](https://github.com/user-attachments/assets/3691e5c7-d657-47a6-bd6f-f63db473a16b)


### 8)	gedit Command

The gedit is a general-purpose text editor. It can be used to create and edit all kinds of text files.

Syntax: gedit file_name
![image](https://github.com/user-attachments/assets/b62b287a-a4cd-4781-9036-d5699174597d)

### 9)	su Command

The su command provides administrative access to another user. In other words, it allows access of the Linux shell to another user.

Syntax: su <user name>

![image](https://github.com/user-attachments/assets/b1e4d545-dfdc-4c9d-acd8-e691837c87e8)

### 10)	mv Command

The mv command is used to move a file or a directory form one location to another location.

Syntax: mv <file name> <directory path>

![image](https://github.com/user-attachments/assets/44f43d41-1bb4-4a55-a356-502775d0d2d0)

 
## 11)	rename Command

The rename command is used to rename files. It is useful for renaming a large group of files.

Syntax: rename 's/old-name/new-name/' files

![image](https://github.com/user-attachments/assets/1e92b2c5-aeff-4069-8f72-d6c80bf2f6fe)

### 12)	head Command

The head command is used to display the content of a file. It displays the first 10 lines of a file.

Syntax: head <file name>

![image](https://github.com/user-attachments/assets/cb5008d9-1ee7-44dc-85ba-1707732deed5)



### 13)	tail Command

The tail command is similar to the head command. The difference between both commands is that it displays the last ten lines of the file content. It is useful for reading the error message.

Syntax: tail <file name>

![image](https://github.com/user-attachments/assets/7c5e40a8-4bf8-4505-aac4-c8a08b248ad9)

 
### 14)	id Command

The id command is used to display the user ID (UID) and group ID (GID).

Syntax: id

![image](https://github.com/user-attachments/assets/486403fb-ee28-4fde-9e61-9736e1782e69)

### 15)	grep Command

The grep is the most powerful and used filter in a Linux system. The 'grep' stands for "global regular expression print." It is useful for searching the content from a file. Generally, it is used with the pipe.

Syntax: command | grep <search word>

![image](https://github.com/user-attachments/assets/7b619f9a-b3d2-4c40-9af8-a61fd56e740c)

### 16)	tr Command

The tr command is used to translate the file content like from lower case to upper case.

Syntax: command | tr <'old'> <'new'>

![image](https://github.com/user-attachments/assets/b75bddcb-ac1c-4f7c-bd34-58eefec73c8d)

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

![image](https://github.com/user-attachments/assets/f049db60-55bd-428d-bc6d-d86644f67a8c)

### 20)	make Command

The make command is used for building and maintaining group of program.

Syntax: make [-f makefile][options]…….[targets]….


### 21)	ifconfig Command

The ifconfig command is used to configure kernel-resident network interface.

Syntax: ifconfig[options][interface]

![image](https://github.com/user-attachments/assets/b16853b0-35de-4eb5-b4cb-2a20b4f07916)

### 22)	chmod 777 Command

The chmod 777 command gives read, write and execute permission to the owner, group and public.

Syntax: chmod 777 file_name
$chmod -R 777 /path/to/file/or/folder
![image](https://github.com/user-attachments/assets/b9cad62d-c588-4123-a321-e8283c33fbb0)

 
### 23)	host Command

The host command is used to display the IP address for a given domain name and vice versa. It performs the DNS lookups for the DNS Query.

Syntax: host <domain name> or <ip address>

![image](https://github.com/user-attachments/assets/ce3cb191-d85a-4e96-be5c-ca5beb35485b)

### 24)	gzip Command

The gzip command is used to truncate the file size. It is a compressing tool. It replaces the original file by the compressed file having '.gz' extension.

Syntax: gzip <file1> <file2> <file3>..
![image](https://github.com/user-attachments/assets/39fe59f5-80b5-4af1-aa3a-bb17d5b266fb)


### 25)	sort Command

The sort command is used to sort files in alphabetical order.

Syntax:sort <file name>

![image](https://github.com/user-attachments/assets/b80a1f86-473b-417e-84cf-e2d02a5843f1)

 
### 26)	cal Command

The cal command is used to display the current month's calendar with the current date highlighted.

Syntax: cal
![image](https://github.com/user-attachments/assets/db5fca00-fa59-422e-8bae-29e15a630b25)



### 27)	clear Command

Linux clear command is used to clear the terminal screen.

Syntax: clear

![image](https://github.com/user-attachments/assets/5308a3ea-7770-4faf-8803-7cddff386535)


### 28)	mail Command

The mail command is used to send emails from the command line.

Syntax: mail -s "Subject" <recipient address>

 
### 29)	df Command

The df command is used to display the disk space used in the file system. It displays the output as in the number of used blocks, available blocks, and the mounted directory.

Syntax: df

![image](https://github.com/user-attachments/assets/fab1e658-525f-4f3d-aeef-2f10027d2f84)


### 30)	find Command

The find command is used to find a particular file within a directory.

Syntax: find.-name”*.pdf”

![image](https://github.com/user-attachments/assets/74ef7067-1b72-46ae-bdbf-147ea825aa82)



## Result:

Thus, the execution of various Linux commands is executed successfully using Ubuntu OS.
