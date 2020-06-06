# Unix or GNU/Linux

The file system used by most Linux distributions is ext4, which should be the file system of your root partition.

The root partition(where linux lives) is denoted with a forward slash ```/```

Everything is a file in Linux.

## Home

```/home/<username>```

This is where you begin. It can look like this:
```John@IBM_PC:~$```

There are some commands to move around, change directories:

```ls```                         list the files in current location

```pwd```                         path of current location

```cd <directory-name-to-open>``` change directory


## Make a new directory

```mkdir MyNewDirectory```

This made me a new directory/folder and I can open it

```cd MyNewDirectory```

## Administrator Rights

```sudo su``` To gain root access and rights to install packages on your system.

## Installing Packages

```dpkg -i PackageName.deb ``` If you have a .deb downloaded package.

```apt install PackageName``` APT is the online repository of packages from where you can get a number of Linux Applications.
