# **Further on Linux**
# Linux File Hierarchy
- ## Linux/UNIX have a specialfile system than windows.
- ## File system is a directorystructure that the OS uses.
# File structure in detail
## **1 / ( root )**
- ##  Every single file and directory starts from the root directory
- ##  The only root user has the right to write under this directory
- ## /root is the root users home directory, which is not the same as /
## **2 bin - Binary executables**
- ## Essential command binaries that need to be available in single-user mode; for all users
- ## e.g cat, ls, cp,pwd
## **3 /boot - Boot loader files**
- ##  Kernel initrd, vmlinux, grub files are located under /boot
 ## **4 /dev - Essential Device files**
- ##  These include terminal devices, usb, or any device attached to the system 
 ## **5 /etc - et cetera**
- ## Contains configuration files required by all programs.
- ## This also contains startup andshutdown shell scripts used tostart/stop individual programs.
 ## **6 /home - Home directory**
- ## Home directories for all users to store their personal files
 ## **7 /lib - Libraries essential for thebinaries in /bin & /sbin**
- ## Library filenames are either ld* or lib*.so
## **8 /media - Mount points forremovable media such as CD-ROMs**
- ## Temporary mount directory for removable devices
## **9 /mnt - Temporarily mounted file**
- ## Temporary mount directory where sysadmins can mount filesystems
## **10 /opt - Optional applicationsoftware packages**
- ## Contains add-on applications from individual vendors.
- ## Add-on applications should be installed under either /opt/ or /opt/ sub-directory 
## **11 /sbin - Essential system binaries**
- ## Just like /bin, /sbin also contains binary executables. The linux commands located under this directory are used typically by system administrator, for system maintenance purpose.
## **12 /tmp - Temporary Files**
- ## Directory that containstemporary files created by system and users. Files under this directory are **deleted** when system is rebooted.
## **13 /usr - User Utilities**
- ## Contains binaries, libraries, documentation, and source-code for second level programs
# **Text Editors**
- ## Programs That user for text processing.
- ## Linux command line text editors
   - ## VIM
    - ## Nano
    - ## Emacs
    - ## Neovim
- ## Linux Graphical Text editors
    - ## Sublime
    - ## Vscode
    - ## Gedit
    - ## Pluma 
    # **VIM**
- ## Before vi the primary editor used on Unix was the line editor
- ## Then then vi editor improved and developed VIM. ( VI iMproved)
- ## The vim editor is: 
   - ## a very powerful
   - ## but at the same time it is cryptic
   - ## It is hard to learn, specially for windows users
- ##  It have to modes
  - ## Command mode -> where you can do commands
  - ## Input mode -> where you can write
  # **Linux User Management**
- ##  On Computer system, person who uses the computer is called **user**
- ## Every Users have Group.
## Users have their own file & applications 
- ## To know our name on linux -> **whoami**  
- ## Those users have power/privilege.
## On linux there's 2 kinds users.
  - ## Root id = 0
  - ## Normal User id start with 1-999
- ## The root user have the power to do everything on linux , but if users want to have a root access they add sudo in front of the command .
- ## **SUDO** = Superuser do , used to pass permission denied