
Linux 101
===============================================================================

Contents
-------------------------------------------------------------------------------

- [Objectives](#objectives)
- [Instructions](#instructions)
- [Solution](#solution)
- [Notes](#notes)



Objectives
-------------------------------------------------------------------------------

Linux 101 \
Difficulty: 1/5 

Visit Ginger Breddie in Santa's Shack on Christmas Island to help him with some
basic Linux tasks. It's in the southwest corner of Frosty's Beach.



Instructions
-------------------------------------------------------------------------------

The North Pole 🎁 Present Maker:

All the presents on this system have been stolen by trolls. Capture trolls by
following instructions here and 🎁's will appear in the green bar below. Run
the command "hintme" to receive a hint.



Solution
-------------------------------------------------------------------------------

<h3> Perform a directory listing of your home directory to find a troll and 
     retrieve a present! </h3>

``` bash
elf@8d56b756a046:~$ ls
```

Output:

```
HELP  troll_19315479765589239  workshop
```

</br>



### Now find the troll inside the troll.

``` bash
elf@8d56b756a046:~$ cat troll_19315479765589239
```

Output:

```
troll_24187022596776786
```

</br>



### Great, now remove the troll in your home directory.

``` bash
elf@8d56b756a046:~$ rm troll_19315479765589239
```

Output:

```
< No output >
```

</br>



### Print the present working directory using a command.

``` bash
elf@8d56b756a046:~$ pwd
```

Output:

```
/home/elf
```

</br>



<h3> Good job but it looks like another troll hid itself in your home 
     directory. Find the hidden troll! </h3>

``` bash
elf@8d56b756a046:~$ ls -a
```

Output:

```
.  ..  .bash_history  .bash_logout  .bashrc  .profile  .troll_5074624024543078  
HELP  workshop
```

</br>



### Excellent, now find the troll in your command history.

``` bash
elf@8d56b756a046:~$ cat .bash_history
```

Output:

```
echo troll_9394554126440791
```

</br>



### Find the troll in your environment variables.

``` bash
elf@8d56b756a046:~$ env
```

Output:

```
SHELL=/bin/bash
TMUX=/tmp/tmux-1050/default,17,0
HOSTNAME=8d56b756a046 
RESOURCE_ID=a0818954-bf5b-4494-93d4-2c22b7b28966
GREENSTATUSPREFIX=presents
PWD=/home/elf                    
LOGNAME=elf
SESSNAME=Troll Wrangler        
z_TROLL=troll_20249649541603754
HOME=/home/elf 
LANG=C.UTF-8
LS_COLORS=rs=0:di=01;34:ln=01;36:mh=00:pi=40;33:so=01;35:do=01;35:bd=40;33;01:c
d=40;33;01:or=40;31;01:mi=00:su=37;41:sg=30;43:ca=30;41:tw=30;42:ow=34;42:st=37
;44:ex=01;32:*.tar=01;31:*.tgz=01;31:*.arc=01;31:*.arj=01;31:*.taz=01;31:*.lha=
01;31:*.lz4=01;31:*.lzh=01;31:*.lzma=01;31:*.tlz=01;31:*.txz=01;31:*.tzo=01;31:
*.t7z=01;31:*.zip=01;31:*.z=01;31:*.dz=01;31:*.gz=01;31:*.lrz=01;31:*.lz=01;31:
*.lzo=01;31:*.xz=01;31:*.zst=01;31:*.tzst=01;31:*.bz2=01;31:*.bz=01;31:*.tbz=01
;31:*.tbz2=01;31:*.tz=01;31:*.deb=01;31:*.rpm=01;31:*.jar=01;31:*.war=01;31:*.e
ar=01;31:*.sar=01;31:*.rar=01;31:*.alz=01;31:*.ace=01;31:*.zoo=01;31:*.cpio=01;
31:*.7z=01;31:*.rz=01;31:*.cab=01;31:*.wim=01;31:*.swm=01;31:*.dwm=01;31:*.esd=
01;31:*.jpg=01;35:*.jpeg=01;35:*.mjpg=01;35:*.mjpeg=01;35:*.gif=01;35:*.bmp=01;
35:*.pbm=01;35:*.pgm=01;35:*.ppm=01;35:*.tga=01;35:*.xbm=01;35:*.xpm=01;35:*.ti
f=01;35:*.tiff=01;35:*.png=01;35:*.svg=01;35:*.svgz=01;35:*.mng=01;35:*.pcx=01;
35:*.mov=01;35:*.mpg=01;35:*.mpeg=01;35:*.m2v=01;35:*.mkv=01;35:*.webm=01;35:*.
ogm=01;35:*.mp4=01;35:*.m4v=01;35:*.mp4v=01;35:*.vob=01;35:*.qt=01;35:*.nuv=01;
35:*.wmv=01;35:*.asf=01;35:*.rm=01;35:*.rmvb=01;35:*.flc=01;35:*.avi=01;35:*.fl
i=01;35:*.flv=01;35:*.gl=01;35:*.dl=01;35:*.xcf=01;35:*.xwd=01;35:*.yuv=01;35:*
.cgm=01;35:*.emf=01;35:*.ogv=01;35:*.ogx=01;35:*.aac=00;36:*.au=00;36:*.flac=00
;36:*.m4a=00;36:*.mid=00;36:*.midi=00;36:*.mka=00;36:*.mp3=00;36:*.mpc=00;36:*.
ogg=00;36:*.ra=00;36:*.wav=00;36:*.oga=00;36:*.opus=00;36:*.spx=00;36:*.xspf=00
;36:
HHCUSERNAME=upsetrobot
AREA=cisantassurfshack
BPUSERHOME=/home/elf
LESSCLOSE=/usr/bin/lesspipe %s %s
TERM=screen
LESSOPEN=| /usr/bin/lesspipe %s
USER=elf                       
TOKENS=linux101
TMUX_PANE=%2
BPUSER=elf
SHLVL=3
LC_ALL=C.UTF-8
PATH=/usr/local/sbin:/usr/local/bin:/usr/sbin:/usr/bin:/sbin:/bin:/usr/games:/u
sr/local/games:/snap/bin
MAIL=/var/mail/elf
LOCATION=7,8
_=/usr/bin/env
```

</br>



### Next, head into the workshop.

``` bash
elf@8d56b756a046:~$ cd workshop
```

Output:

```
< No output >
```

</br>



<h3> A troll is hiding in one of the workshop toolboxes. Use "grep" while
     ignoring case to find which toolbox the troll is in. </h3>

``` bash
elf@8d56b756a046:~/workshop$ grep troll -i *
```

Output:

```
grep: electrical: Is a directory
toolbox_191.txt:tRoLl.4056180441832623
```

</br>



<h3> A troll is blocking the present_engine from starting. Run the
     present_engine binary to retrieve this troll. </h3>

``` bash
elf@8d56b756a046:~/workshop$ chmod +x present_engine
elf@8d56b756a046:~/workshop$ ./present_engine
```

Output:

```
troll.898906189498077
```

</br>


<h3> Trolls have blown the fuses in /home/elf/workshop/electrical. cd into
     electrical and rename blown_fuse0 to fuse0. </h3>

``` bash
elf@8d56b756a046:~/workshop$ mv electrical/blown_fuse0 electrical/fuse0
```

Output:

```
< No output >
```

</br>



### Now, make a symbolic link (symlink) named fuse1 that points to fuse0.

``` bash
elf@8d56b756a046:~/workshop$ cd electrical
elf@8d56b756a046:~/workshop/electrical$ ln -s fuse0 fuse1
```

Output:

```
< No output >
```

</br>



### Make a copy of fuse1 named fuse2.

``` bash
elf@8d56b756a046:~/workshop/electrical$ cp fuse1 fuse2
```

Output:

```
< No output >
```

</br>



<h3> We need to make sure trolls don't come back. Add the characters
     "TROLL_REPELLENT" into the file fuse2. </h3>

``` bash
elf@8d56b756a046:~/workshop/electrical$ echo TROLL_REPELLENT >> fuse2
```

Output:

```
< No output >
```

</br>



### Find the troll somewhere in /opt/troll_den.

``` bash
elf@8d56b756a046:~/workshop/electrical$ cd ./opt/troll_den
elf@8d56b756a046:/opt/troll_den/$ find . -iname *troll* -type f
```

Output:

```
./plugins/embeddedjsp/src/main/java/org/apache/struts2/jasper/compiler/
ParserController.java
./apps/showcase/src/main/resources/tRoLl.6253159819943018
./apps/rest-showcase/src/main/java/org/demo/rest/example/IndexController.java
./apps/rest-showcase/src/main/java/org/demo/rest/example/OrdersController.java
```

</br>
     


### Find the file somewhere in /opt/troll_den that is owned by the user troll.

``` bash
elf@8d56b756a046:/opt/troll_den/$ find . -user troll
```

Output:

```
./apps/showcase/src/main/resources/template/ajaxErrorContainers/
tr0LL_9528909612014411
```

</br>
     


<h3> Find the file created by trolls that is greater than 108 kilobytes and 
     less than 110 kilobytes located somewhere in /opt/troll_den. </h3>

``` bash
elf@8d56b756a046:/opt/troll_den/$ find . -type f -size +108k -size -110k
```

Output:

```
./plugins/portlet-mocks/src/test/java/org/apache/t_r_o_l_l_2579728047101724
```

</br>
     


### List running processes to find another troll.

``` bash
elf@8d56b756a046:/opt/troll_den/$ ps a
```

Output:

```
    PID TTY      STAT   TIME COMMAND
      1 pts/0    Ss+    0:00 /usr/bin/python3 /usr/local/bin/tmuxp load
  12007 pts/2    S+     0:00 /usr/bin/python3 /14516_troll
  14490 pts/3    R+     0:00 ps a
```

</br>
     


<h3> The 14516_troll process is listening on a TCP port. Use a command to have 
     the only listening port display to the screen. </h3>

``` bash
elf@8d56b756a046:/opt/troll_den/$ netstat -l
```

Output:

```
Active Internet connections (only servers)
Proto Recv-Q Send-Q Local Address           Foreign Address         State      
tcp        0      0 0.0.0.0:54321           0.0.0.0:*               LISTEN     
Active UNIX domain sockets (only servers)
Proto RefCnt Flags       Type       State         I-Node   Path
unix  2      [ ACC ]     STREAM     LISTENING     392859279 /tmp/tmux-1050/
default
```

</br>
     


<h3> The service listening on port 54321 is an HTTP server. Interact with this
     server to retrieve the last troll. </h3>

``` bash
elf@8d56b756a046:/opt/troll_den/$ curl localhost:54321
```

Output:

```
troll.73180338045875
```

</br>
     


<h3> Your final task is to stop the 14516_troll process to collect the 
     remaining presents. </h3>

``` bash
elf@8d56b756a046:/opt/troll_den$ pkill troll
```

Output:

```
< No output>
```

</br>
     


### Final Message

Congratulations, you caught all the trolls and retrieved all the presents!
Type "exit" to close...
     


Notes
-------------------------------------------------------------------------------

Source on `find`: 
https://linuxize.com/post/how-to-find-files-in-linux-using-the-command-line/


[Back to top](#linux-101)



<!-- End of file. -->