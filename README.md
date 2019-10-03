Custom Build of dump1090 Skyview Map 
Current build looks like this ![Preview](/Preview.png)
You can apply these modifications by taking the  files in public_html folder of this repository using them to replace the files in your exsisting dump1090 install in /usr/share/dump1090-fa and then restart lighttpd with "systemctl restart lighttpd".

Or use the bash script to install and reload.  
1. Run "wget https://raw.githubusercontent.com/Jxck-S/dump1090-darkX/master/darkX_setup"
2. Enable running of the script to install with "chmod 755 darkX_setup"
3. Run the install script "  ./darkX_setup  "
