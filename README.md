# Virtualization
## Ex.3(A-C) Virtualization: Installation and Configuration of Oracle VirtualBox & Kali Linux, and Execution of Linux Commands

## NAME: RISHI CHANDRAN R

## REG NO: 212223043005

## Aim:

To set up a virtualized environment using Oracle VirtualBox, install Kali Linux as a guest OS, and execute fundamental Linux commands.

## 3.a) Installation and Configuration of Oracle VirtualBox

## Aim:

To install and configure Oracle VM VirtualBox.

## Pre-requisites:

Machine with Internet access

Minimum 4 GB RAM

Sufficient storage space

## Steps:

### 1.Download Oracle VM VirtualBox:

* Visit Oracle VirtualBox Official Site
  
* Download installer for your OS (Windows/macOS/Linux).

### 2.Install Oracle VM VirtualBox (Example: Windows):

* Launch Installer → Allow Changes → Click Next.
  
* Choose Installation Options → Click Next.
  
* Accept Network Interface Warning → Click Yes.
  
* Click Install.
  
* Finish Installation and Launch VirtualBox.

### 3.Configure VirtualBox:

* Open VirtualBox.
  
* Click New → Name VM → Select Type (Linux/Windows) and Version.
  
* Allocate:
  
     * Minimum 2 GB RAM
       
     * Create Virtual Hard Disk (20 GB recommended).
       
* Start Virtual Machine and provide ISO to install OS.

## Result:

Thus, Oracle VM VirtualBox was installed successfully.

## 3.b) Installation and Configuration of Kali Linux

## Aim:

To install and configure Kali Linux in Oracle VirtualBox.

## Pre-requisites:

Oracle VM VirtualBox Installed

4 GB RAM and 20 GB Storage Minimum

Kali Linux ISO image

## Steps:

### 1.Download Kali Linux ISO:

* Visit Kali Linux Official Site
  
* Download 64-bit ISO (Installer version).
  
### 2.Create a New Virtual Machine:

* Open VirtualBox → Click New.
  
* Name: "Kali Linux" → Type: Linux → Version: Debian (64-bit).
  
### 3.Allocate Memory:

* Minimum 2 GB RAM (recommended 4 GB).
  
### 4.Create Virtual Hard Disk:

* Select VDI (VirtualBox Disk Image).
  
* Choose Dynamically allocated.
  
* Set Disk size to 20 GB or more.
  
### 5.Configure ISO Image:

* Settings → Storage → Controller: IDE → Empty CD → Choose Disk File → Select Kali Linux ISO.
  
### 6.Start Installation:

* Boot Virtual Machine → Choose Graphical Install.
  
* Set Language, Region, Keyboard.
  
* Configure Network → Set Hostname (e.g., kali).
  
* Set root password.
  
* Disk Partitioning: Use entire disk → All files in one partition.
  
* Install System → Install GRUB Bootloader → Finish Installation.
  
### 7.Login to Kali Linux:

* Use root credentials.
  
### 8.(Optional) Install Guest Additions:

* Devices → Insert Guest Additions CD Image → Follow steps inside Kali.
  
## Snapshots:

AWS Account Creation Snapshot

Snapshot 1: Installing Oracle VirtualBox
<img width="1034" height="537" alt="Screenshot 2025-10-16 090703" src="https://github.com/user-attachments/assets/a31cd8d2-d291-4891-83eb-bffe05c34d6e" />




Snapshot 2: Kali Running in Virtual

<img width="1032" height="631" alt="image" src="https://github.com/user-attachments/assets/8c5faaba-f5d3-4318-9366-9d0276aebd5b" />



## 3.c) Execution of Linux Commands in Kali

## About Linux:

* Open-source operating system.
  
* Kernel manages communication between hardware and software.
  
* Commands are case-sensitive.
    
## Linux Commands:

### 1.ls Command

The ls command is used to display a list of content of a directory.

#### Syntax:
```
     ls
```
<img width="1039" height="65" alt="image" src="https://github.com/user-attachments/assets/84a7807a-22c7-4f2c-8afc-9ca744bb9107" />



### 2.pwd Command
The pwd command is used to display the location of the current working directory.

#### Syntax:
```
   pwd
```
<img width="577" height="63" alt="image" src="https://github.com/user-attachments/assets/a79f78d4-b32b-4082-96dc-1548f26de598" />



### 3.mkdir Command

The mkdir command is used to create a new directory under any directory.

#### Syntax:
```
    mkdir <directory_name>
```
<img width="1036" height="79" alt="image" src="https://github.com/user-attachments/assets/dbf7fc69-99fc-4b5c-a2c6-db8b79bd5675" />


### 4.rmdir Command

The rmdir command is used to delete a directory.

#### Syntax:
```
  rmdir <directory_name>
```
<img width="1037" height="77" alt="image" src="https://github.com/user-attachments/assets/4b219b34-ea1f-428d-8cf3-fcab5d55cc3a" />



### 5.cd Command The cd command is used to change the current directory

#### Syntax:
```
    cd <directory_name>
```
<img width="659" height="61" alt="image" src="https://github.com/user-attachments/assets/09b8dd64-0bcc-4c5f-a5a1-9cdcdb4459b7" />

### 6.cat Command

The cat command is a multi-purpose utility in the Linux system. It can be used to create a file, display content ofthe file, copy the content of one file to another file, and more.

#### Syntax:
```
    cat [options] [file_name]
```
<img width="1039" height="115" alt="image" src="https://github.com/user-attachments/assets/7eaa2999-9d85-4429-a135-fea65ec067a8" />


### 7.cp Command

The cp command is used to copy a file or directory.

#### Syntax:
```
   cp [source] [destination]
```
<img width="921" height="116" alt="image" src="https://github.com/user-attachments/assets/18d76e90-7da3-4a05-a69c-1b08c980e321" />


### 8. gedit Command


#### Syntax:
```
    gedit [source]
```
<img width="1040" height="280" alt="image" src="https://github.com/user-attachments/assets/56f03cf3-09be-4581-b5df-6e68c1578e99" />



### 9. su Command

#### Syntax :
```
    su
```
<img width="657" height="86" alt="image" src="https://github.com/user-attachments/assets/61c2c394-c447-4943-b459-71717cb9f460" />


### 10.cd Command



## Syntax:

   cd [filename]

<img width="925" height="261" alt="image" src="https://github.com/user-attachments/assets/0de5b8d7-d065-4bad-9e11-a138b4fd3f9e" />


### 11. head Command



#### Syntax:
```
   head [filename]
```
<img width="920" height="65" alt="image" src="https://github.com/user-attachments/assets/f39d8eab-cebf-4e51-aee5-e9c71cd71564" />


### 12. id Command



#### Syntax:
```
   id
```
<img width="1036" height="40" alt="image" src="https://github.com/user-attachments/assets/cb99fbeb-4426-48aa-8c84-ea9e942e006f" />


### 13. df Command



#### Syntax:
```
   df
```
<img width="890" height="289" alt="image" src="https://github.com/user-attachments/assets/0bcf0d2d-b69d-4f18-8c8c-a28021ad3147" />



### 14. clear Command



#### Syntax:
```
   clear
```
<img width="869" height="98" alt="image" src="https://github.com/user-attachments/assets/86646b20-72b7-48a2-aea0-69e0bc33860e" />



### 15.cal Command



#### Syntax:
```
   cal
```
<img width="817" height="240" alt="image" src="https://github.com/user-attachments/assets/ac9251a9-9ab5-4b1f-a5e3-4746a7d650b3" />


## Result:

Thus, various Linux commands were executed successfully in Kali Linux virtual machine.
