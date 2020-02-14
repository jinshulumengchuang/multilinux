# multilinux
Multlinux allows you to run multiple Linux OSes at one time.It uses chroot feature in Linux. Multilinux allows 
you to run multiple Linux OSes with only one kernel,all linux OSes will share hardware resouces and use them directly.  
<br>installation<br>
Download the three bash script files : mountlinux,startlinux and switchlinux ,then copy them to /usr/bin.Use chmod to give them execute permission.
<br>How to use<br>
To use multilinux, you need install Xephyr to you system.You also need to create a bash file named 'desktop' in other OSes  you want to run.You should store it in the OS's '/'.This file should include command to start GUI in this OS.Like 'dbus-launch mate-session' 'startkde' 'gnome-session'
<br><br>
<br>mountlinux linuxroot<br>
<br>Use mountlinux to initialize a Linux OS<br>
<br>startlinx linuxroot :Display Number<br>
<br>startlinux allows you to run another Linux OS in window.Just Like virtualmachine.In order to run GUI,startlinux needs you to specify a Xwindow display number.<br>
<br>switchlinux linuxroot<br>
<br>switch to another Linux system, use 'killall Xephyr' to exit. <br>
