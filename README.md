bkp
===
<b>Description</b><br>
Linux/Unix Shell script to backup file or directory to $HOME. Script creates directory ~/backup/&lt;current date&gt;/.
Then it is copying target file/dir to this dir with current time prefix adding.
If there is directory passed as a target it will be zipped and copied in the same way.

<b>Installation</b><br>
Place file to some exectable path (i.e. /usr/local/bin/), and set execute-flag via<br>
<i>chmod +x /usr/local/bin/bkp</i>

<b>Usage</b><br>
Before doing sudo vim /etc/postfix/postfix.rc just make<br>
<i>bkp /etc/postfix/postfix.rc</i>
And almost all will be OK. 
