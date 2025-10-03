## Ex.3 Virtualization: Installation and Configuration of Oracle VirtualBox & Kali Linux, and Execution of Linux Commands
## NAME: ILEVARASEN S
## REG NUMBER: 212224040120
## Aim:
To set up a virtualized environment using Oracle VirtualBox, install Kali Linux as a guest OS, and execute fundamental Linux commands.

## 3.a) Installation and Configuration of Oracle VirtualBox
## Aim:
To install and configure Oracle VM VirtualBox.

## Pre-requisites:
- Machine with Internet access
- Minimum 4 GB RAM
- Sufficient storage space
## Steps:
1.Download Oracle VM VirtualBox:

- Visit Oracle VirtualBox Official Site
- Download installer for your OS (Windows/macOS/Linux).

2.Install Oracle VM VirtualBox (Example: Windows):

- Launch Installer → Allow Changes → Click Next.
- Choose Installation Options → Click Next.
- Accept Network Interface Warning → Click Yes.
- Click Install.
- Finish Installation and Launch VirtualBox.

3.Configure VirtualBox:

- Open VirtualBox.
- Click New → Name VM → Select Type (Linux/Windows) and Version.
- Allocate:
  
     Minimum 2 GB RAM
  
     Create Virtual Hard Disk (20 GB recommended).
  
- Start Virtual Machine and provide ISO to install OS.
## Result:
Thus, Oracle VM VirtualBox was installed successfully.

## 3.b) Installation and Configuration of Kali Linux
## Aim:
To install and configure Kali Linux in Oracle VirtualBox.

## Pre-requisites:
- Oracle VM VirtualBox Installed
- 4 GB RAM and 20 GB Storage Minimum
- Kali Linux ISO image
## Steps:

1.Download Kali Linux ISO:
- Visit Kali Linux Official Site
- Download 64-bit ISO (Installer version).
  
2.Create a New Virtual Machine:
- Open VirtualBox → Click New.
- Name: "Kali Linux" → Type: Linux → Version: Debian (64-bit).

3. Allocate Memory:
- Minimum 2 GB RAM (recommended 4 GB).
  
4.Create Virtual Hard Disk:
- Select VDI (VirtualBox Disk Image).
- Choose Dynamically allocated.
- Set Disk size to 20 GB or more.
  
5.Configure ISO Image:
- Settings → Storage → Controller: IDE → Empty CD → Choose Disk File → Select Kali Linux ISO.
  
6.Start Installation:
- Boot Virtual Machine → Choose Graphical Install.
- Set Language, Region, Keyboard.
- Configure Network → Set Hostname (e.g., kali).
- Set root password.
- Disk Partitioning: Use entire disk → All files in one partition.
- Install System → Install GRUB Bootloader → Finish Installation.
  
7.Login to Kali Linux:
- Use root credentials.
  
8.(Optional) Install Guest Additions:
- Devices → Insert Guest Additions CD Image → Follow steps inside Kali.
  
## Snapshots:

AWS Account Creation Snapshot
## Snapshot 1: Installing Oracle VirtualBox image
<img width="1909" height="986" alt="image" src="https://github.com/user-attachments/assets/b10cab9f-2424-4c05-9afd-3994ba414fb2" />

## Snapshot 2: Kali Running in Virtual image
<img width="1651" height="901" alt="image" src="https://github.com/user-attachments/assets/9b640e46-02a7-46b2-9f74-2d07c7d88d5e" />


## Result:
Thus, Kali Linux guest OS was installed and configured successfully.

## 3.c) Execution of Linux Commands in Kali
## About Linux:
- Open-source operating system.
- Kernel manages communication between hardware and software.
- Commands are case-sensitive.
## Commands:
## 1) ls Command
The ls command is used to display a list of content of a directory.

Syntax: ls

<img width="605" height="64" alt="image" src="https://github.com/user-attachments/assets/41179842-eed0-4557-bb55-f8abb14a44ba" />


## 2) pwd Command
The pwd command is used to display the location of the current working directory.

Syntax: pwd

<img width="231" height="73" alt="image" src="https://github.com/user-attachments/assets/4abc06c1-9f89-4062-a3d9-7751393c72b7" />


## 3) mkdir Command
The mkdir command is used to create a new directory under any directory.

Syntax: mkdir

<img width="412" height="140" alt="image" src="https://github.com/user-attachments/assets/314ae5bb-b5c8-4bab-8db0-0b052e25429e" />



## 4) rmdir Command
The rmdir command is used to delete a directory.

Syntax: rmdir

<img width="617" height="125" alt="image" src="https://github.com/user-attachments/assets/506f92aa-84e8-4823-88c0-c8775218a521" />

## 5) cd Command
The cd command is used to change the current directory.

Syntax: cd

<img width="291" height="150" alt="image" src="https://github.com/user-attachments/assets/6f4bcb88-9946-40db-92be-4099c260bccc" />

## 6) cat Command
The cat command is a multi-purpose utility in the Linux system. It can be used to create a file, display content of the file, copy the content of one file to another file, and more.

Syntax: cat [OPTION]... [FILE]..

<img width="276" height="189" alt="image" src="https://github.com/user-attachments/assets/14c45bf1-0c81-4c2b-b4e7-3d2928722237" />

## 7) cp Command
The cp command is used to copy a file or directory.

Syntax: cp

<img width="415" height="231" alt="image" src="https://github.com/user-attachments/assets/8cb6709d-2f3a-4411-be81-d04b09daba64" />


## 8) gedit Command
The gedit is a general-purpose text editor. It can be used to create and edit all kinds of text files.

Syntax: gedit file_name

<img width="437" height="91" alt="image" src="https://github.com/user-attachments/assets/e8d8f86c-53fb-4e13-b9fe-1205dfa37344" />

## 9) su Command
The su command provides administrative access to another user. In other words, it allows access of the Linux shell to another user.

Syntax: su

<img width="271" height="70" alt="image" src="https://github.com/user-attachments/assets/fe127b31-f4ce-4e45-93e5-be19653503e3" />


## 10) mv Command
The mv command is used to move a file or a directory form one location to another location.

Syntax: mv

<img width="269" height="271" alt="image" src="https://github.com/user-attachments/assets/7c0d0146-080d-44d2-901b-4b881f8c5db1" />


## 11) rename Command
The rename command is used to rename files. It is useful for renaming a large group of files.

Syntax: rename 's/old-name/new-name/' files

<img width="428" height="306" alt="image" src="https://github.com/user-attachments/assets/1637d6cb-5b5c-4069-811a-8cf6f1c5b7c7" />


## 12) head Command
The head command is used to display the content of a file. It displays the first 10 lines of a file.

Syntax: head

<img width="274" height="257" alt="image" src="https://github.com/user-attachments/assets/1cc8bc0a-acff-4d3a-a52c-eb4ad3a0388a" />


## 13) tail Command
The tail command is similar to the head command. The difference between both commands is that it displays the last ten lines of the file content. It is useful for reading the error message.

Syntax: tail

<img width="285" height="119" alt="image" src="https://github.com/user-attachments/assets/265f5bc5-93c4-4f08-9fca-4bf8808373bc" />

## 14) id Command
The id command is used to display the user ID (UID) and group ID (GID).

Syntax: id

<img width="635" height="117" alt="image" src="https://github.com/user-attachments/assets/3c36c4f3-f2cb-4dbc-b986-82df55c0d1a9" />


## 15) grep Command
The grep is the most powerful and used filter in a Linux system. The 'grep' stands for "global regular expression print." It is useful for searching the content from a file. Generally, it is used with the pipe.

Syntax: command | grep

<img width="272" height="49" alt="image" src="https://github.com/user-attachments/assets/a0a98bac-a8b3-4612-8a93-d6ba442bdfd0" />

## Result:
Thus, the execution of various Linux commands is executed successfully using Kali Linux.
