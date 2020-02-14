# multilinux
Multlinux allows you to run multiple Linux OSes at one time.It uses chroot feature in Linux. Multilinux allows 
you to run multiple Linux OSes with only one kernel,all linux OSes will share hardware resouces and use them directly.  
<br>Installation<br>
Download the three bash script files : mountlinux,startlinux and switchlinux ,then copy them to /usr/bin.Use chmod to give them execute permission.
<br>
<br>How to use<br>
To use multilinux, you need install Xephyr to you system.You also need to create a bash file named 'desktop' in other OSes  you want to run.You need to  store it in the OS's '/'.This file should include command to start GUI in this OS.Like 'dbus-launch mate-session' 'startkde' 'gnome-session'
<br>mountlinux linuxroot
<br>Use mountlinux to initialize a Linux OS
<br>startlinx linuxroot :Display Number
<br>startlinux allows you to run another Linux OS in window.Just Like virtualmachine.In order to run GUI,startlinux needs you to specify a Xwindow display number.
<br>switchlinux linuxroot
<br>switch to another Linux system, use 'killall Xephyr' to exit. 
