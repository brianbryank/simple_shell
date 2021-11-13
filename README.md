# SIMPLE SHELL

     Date:22-2021-10
     ALX- school

# Description

Shell is an environment in which we can run our commands, programs, and shell scripts.There are different flavors of a shell, just as there are different flavors of operating systems.Each flavor of shell has its own set of recognized commands and functions.


# Requirements

simple_shell is designed to run in the Ubuntu linux environment and to be compiled using the GNU compiler collection v. gcc 4.8.4 with flags -Wall, -Werror, -Wextra, and -pedantic.

# Installation

* Clone this [repository](https://github.com/Joy879/simple_shell.git)
* Change directories into the repository:   
          cd simple_shell
* Compile using:  
          gcc -Wall -Werror -Wextra -pedantic *.c -o hsh
* Run the shell:  
          ./hsh
   
# Example
     1.
          $ ./hsh
          $ pwd
          /home/username/
          $ ^D

     2.
          $ ./hsh
          $ ls -l /tmp
          -rw------- 1 username username 0 Dec 5 12:09 config-err-aAMZrR
          drwx------ 3 root root 4096 Dec 5 12:09 systemd-private-062a0eca7f2a44349733e78cb4abdff4-colord.service-V7DUzr
          drwx------ 3 root root 4096 Dec 5 12:09 systemd-private-062a0eca7f2a44349733e78cb4abdff4-rtkit-daemon.service-ANGvoV
          drwx------ 3 root root 4096 Dec 5 12:07 systemd-private-062a0eca7f2a44349733e78cb4abdff4-systemd-timesyncd.service-CdXUtH
          -rw-rw-r-- 1 username username 0 Dec 5 12:09 unity_support_test.0
          $ ^D
          $

     3.run the program by executing the follwing command
          $ ./hsh
          $ ls

# List of functions and system calls we are allowed to use:

* access (man 2 access)
* chdir (man 2 chdir)
* close (man 2 close)
* closedir (man 3 closedir)
* execve (man 2 execve)
* exit (man 3 exit)
* fork (man 2 fork)
* free (man 3 free)
* fstat (man 2 fstat)
* getcwd (man 3 getcwd)
* getline (man 3 getline)
* kill (man 2 kill)
* lstat (man 2 lstat)
* malloc (man 3 malloc)
* open (man 2 open)
* opendir (man 3 opendir)
* perror (man 3 perror)
* read (man 2 read)
* readdir (man 3 readdir)
* signal (man 2 signal)
* stat (man 2 stat)
* strtok (man 3 strtok)
* wait (man 2 wait)
* waitpid (man 2 waitpid)
* wait3 (man 2 wait3)
* wait4 (man 2 wait4)
* write (man 2 write)
* _exit (man 2 _exit)

# Authors

Brian Kiplangat-brianbyank

Joy Wanjiru-Joy879
