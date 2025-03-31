# Lab 2
## Overview
This lab's purpose is to serve as an introduction to the unix commands necessary to perform basic navigations and functions using a raspberry py.
By connecting to a raspberry pi remotely and running commands in its terminal, I was able to acquire the screenshots necessary to detail my results.

### hostname
![hostname](https://github.com/VictorAfonso1208/CPE-322/blob/main/Labs/Lab2/Lab2Images/hostname.png)

This command gives the name of the device being used. I kept it to "raspberry pi."

### env
![env](https://github.com/VictorAfonso1208/CPE-322/blob/main/Labs/Lab2/Lab2Images/env.png)

This command gives information on the environment being utilized, such as visual information that can be readily seen by the user.

### ps
![ps](https://github.com/VictorAfonso1208/CPE-322/blob/main/Labs/Lab2/Lab2Images/ps.png)

This command displays currently running processes. As one can see, there isn't much going on here.

### pwd
![pwd](https://github.com/VictorAfonso1208/CPE-322/blob/main/Labs/Lab2/Lab2Images/pwd.png)

This command displays the full directory of where the user is working, in this case mine own.

### git clone
![git clone](https://github.com/VictorAfonso1208/CPE-322/blob/main/Labs/Lab2/Lab2Images/clone.png)

This command takes a github respository directory and copies it to the pi's own file system. Now I have the entirety of Kevin Lu's github repository on my pi.

### cd iot
![cd iot](https://github.com/VictorAfonso1208/CPE-322/blob/main/Labs/Lab2/Lab2Images/cd%20iot.png)

This command changes my working directory to that of the iot folder.

### ls
![ls](https://github.com/VictorAfonso1208/CPE-322/blob/main/Labs/Lab2/Lab2Images/ls.png)

This command lists all the folders immediately below the working directory.

### cd
![cd](https://github.com/VictorAfonso1208/CPE-322/blob/main/Labs/Lab2/Lab2Images/cd.png)

This command changes my working directory to what it was previously; it moves me "up."

### df
![df](https://github.com/VictorAfonso1208/CPE-322/blob/main/Labs/Lab2/Lab2Images/df.png)

This command displays info on my disk space usage.

### mkdir demo
![mkdir](https://github.com/VictorAfonso1208/CPE-322/blob/main/Labs/Lab2/Lab2Images/cd.png)

This command makes a new directory, demo. Note that this screenshot was taken after I had already make said directory.

### cd demo
![cd demo](https://github.com/VictorAfonso1208/CPE-322/blob/main/Labs/Lab2/Lab2Images/cd%20demo.png)

This command changes my working directory to the demo I just created.

### nano file
![nano file](https://github.com/VictorAfonso1208/CPE-322/blob/main/Labs/Lab2/Lab2Images/nano%20file.png)

This command opens a nano text file named file that I was able to write text to.

### cat file
![cat file](https://github.com/VictorAfonso1208/CPE-322/blob/main/Labs/Lab2/Lab2Images/cat%20file.png)

This command reads and prints the text in "file."

### cp file file1
![cp file file1](https://github.com/VictorAfonso1208/CPE-322/blob/main/Labs/Lab2/Lab2Images/cp%20file.png)

This command copies my file into a new file, "file1."

### mv file file2
![mv file file2](https://github.com/VictorAfonso1208/CPE-322/blob/main/Labs/Lab2/Lab2Images/mv%20file.png)

This command moves my first file into a new directory, file2.

### rm file2
![rm file2](https://github.com/VictorAfonso1208/CPE-322/blob/main/Labs/Lab2/Lab2Images/rm%20file.png)

This command deletes my newly made file2 directory.

### clear
![clear](https://github.com/VictorAfonso1208/CPE-322/blob/main/Labs/Lab2/Lab2Images/clear.png)

This command clears all previous outputs in my terminal window.

### man uname
![man uname](https://github.com/VictorAfonso1208/CPE-322/blob/main/Labs/Lab2/Lab2Images/man%20uname.png)

This command prints a sort of user manual for the user, with various printing options.

### uname -a
![uname -a](https://github.com/VictorAfonso1208/CPE-322/blob/main/Labs/Lab2/Lab2Images/uname%20-a.png)

This command prints information about the system being used, such as its OS.

### ifconfig
![ifconfig](https://github.com/VictorAfonso1208/CPE-322/blob/main/Labs/Lab2/Lab2Images/ifconfig.png)

This command allows me to view and change the configuration of the network interfaces on my system.

### ping localhost
![ping localhost](https://github.com/VictorAfonso1208/CPE-322/blob/main/Labs/Lab2/Lab2Images/ping%20localhost.png)

This command pings my local network and displays information such as packets sent and the time taken to send.

### netstat
![netstat](https://github.com/VictorAfonso1208/CPE-322/blob/main/Labs/Lab2/Lab2Images/netstat1.png)
![netstat2](https://github.com/VictorAfonso1208/CPE-322/blob/main/Labs/Lab2/Lab2Images/netstat2.png)

This command displays various network related information such as network connections, routing tables, interface statistics
