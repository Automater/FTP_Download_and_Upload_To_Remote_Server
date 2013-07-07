Lets you connect to remote server to download and upload file or database via FTP.

![Alt text](http://173.0.133.251/images/GitHub/FTP_Download_and_Upload.gif "Download and Upload Files")

1)  Downloading is handled by these 2 files *

a)  download.bat

b)  download.ftp


2)  Uploading is handled by these 2 files *

a)  upload.bat

b)  upload.ftp

* Use Notepad to edit their source and target drive and folder locations and the filename to download or upload.



#### Note: ####

1)  The above includes a "live" connection to a web server with a working website.  You may freely use it to test and customise the script for downloading or uploading purposes but please handle it with care by not uploading large files or sensitive / illegal materials.

![Alt text](http://173.0.133.251/images/GitHub/ASCII-Binary.gif "ASCII and Binary files")

> 2)  Rule of Thumb - 

> a)  Use ASCII only for transferring HTML Documents (The scripts are using ASCII by default).

> b)  Everything else - goes Binary (or raw data or all files depending on your program) (Add the word __bin__ in a new line after the server login lines)




#### Known Issues: ####

1)  I ran the batch (.bat) file for accessing remote web server via FTP.  At first attempt, it was not successful because Windows Firewall will block and prompt if you were to allow it.

![Alt text](http://173.0.133.251/images/GitHub/Firewall_Blocked_Allow_Access.gif "Firewall Prompt for Permission")

2)  Then I repeat the run (.bat) again and it ran successfully and downloaded a database file in the native DOS Command prompt.

![Alt text](http://173.0.133.251/images/GitHub/DOS-Downloaded.gif "Downloaded using DOS prompt")

3)  But when I run in ACL v10, it will not work even after I have allowed it as a private network in the Firewall and I added "ACL Analytics 10" software into the "list of allowed programs" in the Windows Firewall.

![Alt text](http://173.0.133.251/images/GitHub/In-ACL-Not-Downloading-Unless-Firewall-Switched-Off.gif "In ACL Not Downloading Unless Firewall Switched Off")

![Alt text](http://173.0.133.251/images/GitHub/list_of_allowed_programs.gif "ACL v10 in List of Allowed Programs")

4)  Finally, I disabled the Windows Firewall altogether and then IT'LL WORK running the batch file in ACL v10.

![Alt text](http://173.0.133.251/images/GitHub/Firewall-Off.gif "Firewall Switched Off")


#### Questions? ####

Email me: patrickong@gmail.com
