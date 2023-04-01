# Splunk
My hands-on Splunk learning journey
[Installing and Configuring SE on Ubuntu VM.pdf](https://github.com/twitchy-fingers/Splunk/files/11128602/Installing.and.Configuring.SE.on.Ubuntu.VM.pdf)


Installing and Configuring SE 
 
Prerequisites for Installation 
•	You can install the Splunk Enterprise Debian package only into the default location, /opt/splunk • 	This location must be a regular directory and cannot be a symbolic link.  
•	You must have access to the root user or have sudo permissions to install the package.  
•	The package does not create environment variables to access the Splunk Enterprise installation directory. You must set those variables on your own.  
Note: If you need to install Splunk Enterprise somewhere else, or if you use a symbolic link for /opt/splunk, then use a tar file to install the software.  
 
Installation Procedure for .deb file 
•	Proceed to splunk.com to download the .deb package. 

 
•	Cancel the download process and click on “Download via Command Line (wget)”.  
  
 
•	Copy the entire command and proceed to your Terminal. 
•	On the Terminal, change directory to /Downloads. 
•	In the /Downloads directory, paste the command gotten from splunk.com and click enter (this will download the SE). 
•	After downloading SE, type the command sudo apt install ./splunk_package_name.deb to install SE. 
  
 
•	Change user to root by typing sudo su. 
•	Change directory by typing “cd /opt/splunk/bin”. Note: to start splunk, you need to navigate to Splunk’s bin directory. 
•	On /bin type “./splunk start --accept-license” to start up splunk. You will be required to create a username and password for your SE login. 
  
 
•	After start, the web interface URL for your splunk SE will be displayed.  
  
 
•	Copy the URL and paste in your web browser. Click enter and proceed to the address.  
•	Enter your SE username and password, then enter.  
 
  
 
•	You have successfully installed and ran your SE. 
  
