=> Linux is a kernel.
=> Linux is a kernel, not an operating system. The kernel is the core of the operating system.
=> Routers have ram,cpu and some storage :- It uses linux based os.
=> Kernel is low end software.
=> Ubuntu,Redhat,Linux,Mint --> Linux kernel --> Hardware resource.
=> To communicate with hardware we need os because hardware understand only 0 and 1.
=> Windows --> Windows kernel --> Hardware resource - 8 core cpu.

=> A computer requires both hardware and software to operate.
=> There has to be a layer of software that operates the hardware at low level which is kernel.

what makes linux special ?
=> It is open source.
=> It is free.
=> It is fast.
=> Anyone can change the source code of linux and use as they want.
=> Any unnecessary feature can be removed making it faster.


NOTE :- To create fast server use python -m http.server 8000
Note :- To connect to aws-server using ssh use :- ssh -i "private_key" ec2-user@65.1.136.92


==> If gui is used :- gui -> cli -> kernel -> machine language -> hardware (hard-disk). (hence cli is faster)

=> Linux is more secure.
=> Linux is more stable.
=> Linux is open-source.
=> Simplified updates for all installed software.
=> Light-weight.
=> Multiuser and multitask.
=> Multiple distribution -> Redhat,fedora,debian etc.
=> Unlimited user can connect to same linux server.
=> Linux is faster because in linux we directly write command,But in windows we use GUI to do work. Windows converts that GUI to command in backend that's why it is heavy as well as slower.
=> root user logges in /root directory all other users logs in /home/user directory.
=> /boot -> It contains bootable file for linux, bootable files requires when our machine starts with the help of bootable file only our hardware is able to communicate with os.
=> /etc -> it contains all configuration file -> all hardware related config file found here.
=> /usr -> by default software are installed in this directory.
=> /opt -> optional application software packages.
=> /bin -> it contains commands used by all users (including root user).
=> If the command is written in /bin directory it can be run by any user but if the command is written in /sbin directory it can be only run by root user.


=> commands ::-
i) to become root user from normal-user 'sudo su root'
ii) to list all directory :- 'ls'
iii) to create a file using cat command :- 'cat > file_name' (press ctr+D to save and exit) (using '>' symbol overrides the content of the previous file) .. to append content we can use '>>' sign 
iv) to delete a file :- 'rm file_name'
v) copy the content of file1 to file2 using cat command :- 'cat file1 > file2'
vi) cat > file_name ('>' symbol helps to write and '<' symbol helps us to read).
vii) if u want to reverse the content of the file u can use tac command ex :- tac file_name
viii) u can also use touch command to create files ex :- touch file_name but to write something again we can use cat > file_name.
ix) using touch command we can change the access and modify time of the file creation as well.
x) to change the access time 'touch -a file_name'
xi) to change the modification time 'touch -m file_name'



==> If we put .file (dot) in filename while creating it will be hidden .
==> ls -l is used to long listing.
==> ls -a shows hidden files as well.