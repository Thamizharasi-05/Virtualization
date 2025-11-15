# Ex.3 Virtualization: Installation and Configuration of Oracle VirtualBox & Kali Linux, and Execution of Linux Commands
## NAME: JAYASURYA B
## REGISTER NUMBER: 212224100026
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

## Snapshot 2: Ubuntu Running in Virtual image
![1](https://github.com/user-attachments/assets/971a434c-618c-430e-b4cd-f25d78297c4c)


## Result:
Thus, Linux guest OS was installed and configured successfully.

## 3.c) Execution of Linux Commands in Kali
## About Linux:
- Open-source operating system.
- Kernel manages communication between hardware and software.
- Commands are case-sensitive.
## Commands:
## 1) ls Command
The ls command is used to display a list of content of a directory.

Syntax: ls

![ls](https://github.com/user-attachments/assets/4df4643b-cc00-41cf-93cd-781c403514f6)


## 2) pwd Command
The pwd command is used to display the location of the current working directory.

Syntax: pwd

![pwd](https://github.com/user-attachments/assets/cc16f720-1d30-4e06-94dc-685c1387f9b4)

## 3) mkdir Command
The mkdir command is used to create a new directory under any directory.

Syntax: mkdir

![WhatsApp Image 2025-10-03 at 13 27 12_0c29f469](https://github.com/user-attachments/assets/e515c07c-020a-4aec-a141-53194462bee2)


## 4) rmdir Command
The rmdir command is used to delete a directory.

Syntax: rmdir

![rem](https://github.com/user-attachments/assets/3caa156a-b1ca-4c31-b860-f7146e271b64)


## 5) cd Command
The cd command is used to change the current directory.

Syntax: cd

![cd](https://github.com/user-attachments/assets/a646588c-ddf5-4476-83d1-69b008ab6a0a)


## 6) cat Command
The cat command is a multi-purpose utility in the Linux system. It can be used to create a file, display content of the file, copy the content of one file to another file, and more.

Syntax: cat [OPTION]... [FILE]..

![cat](https://github.com/user-attachments/assets/e799a652-aae2-4511-bccc-c873b1da1228)

## 7) cp Command
The cp command is used to copy a file or directory.

Syntax: cp

![cp](https://github.com/user-attachments/assets/8cb5392a-8228-4482-9c83-9e92e9bd466d)

## 8) gedit Command
The gedit is a general-purpose text editor. It can be used to create and edit all kinds of text files.

Syntax: gedit file_name

![grt](https://github.com/user-attachments/assets/fcb547ad-80ab-4978-9139-6a3d8d8b3661)

## 9) head Command
The head command is used to display the content of a file. It displays the first 10 lines of a file.

Syntax: head

![head](https://github.com/user-attachments/assets/93179201-47a4-48b9-ba87-9441519253bf)

## 10) tail Command
The tail command is similar to the head command. The difference between both commands is that it displays the last ten lines of the file content. It is useful for reading the error message.

Syntax: tail

![tail](https://github.com/user-attachments/assets/e806880c-d62b-46ed-a94f-a9513754d665)

## 11) id Command
The id command is used to display the user ID (UID) and group ID (GID).

Syntax: id

![id](https://github.com/user-attachments/assets/1ed129fa-57e9-47fd-830f-b281b607732b)

## 12) grep Command
The grep is the most powerful and used filter in a Linux system. The 'grep' stands for "global regular expression print." It is useful for searching the content from a file. Generally, it is used with the pipe.

Syntax: command | grep

![ge](https://github.com/user-attachments/assets/b306b4b3-f048-44f0-8b3f-c1b5f3535adf)

## 13) tr Command
The tr command is used to translate the file content like from lower case to upper case.

Syntax: command | tr <'old'> <'new'>

![tr](https://github.com/user-attachments/assets/b4617c13-dd09-4ae5-89bc-c0a4fe3b3afd)


## 14) sort Command
The sort command is used to sort files in alphabetical order.

Syntax:sort

![sort](https://github.com/user-attachments/assets/f4eb6f5b-52f7-460a-87ae-14a3d31c0b01)

## 15) cal Command
The cal command is used to display the current month's calendar with the current date highlighted.

Syntax: cal

![cal](https://github.com/user-attachments/assets/1dbc2513-1d9f-4701-bf47-2276ab7d14a5)

## Result:
Thus, the execution of various Linux commands is executed successfully using Linux.

