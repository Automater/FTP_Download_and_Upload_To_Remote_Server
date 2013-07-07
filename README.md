This script lets you connect via FTP to remote server to download and upload files.

![Alt text](http://173.0.133.251/download/downloadandupload.gif "Download and Upload Files")


1)  Downloading is handled by these 2 files (Use Notepad to edit their source and target drive and folder locations and the filename to download)

a)  download.bat

b)  download.ftp


2)  Uploading is handled by these 2 files (Use Notepad to edit their source and target drive and folder locations and the filename to upload)

a)  upload.bat

b)  upload.ftp


Note:
-----

1)  The above includes a "live" connection to a web server with a working website.  You may freely use it to test and customise the script for downloading or uploading purposes but please handle it with care by not uploading large files or sensitive / illegal materials.

![Alt text](http://173.0.133.251/download/ASCII-Binary.gif "ASCII and Binary files")

> 2)  Rule of Thumb - 

> a)  Use ASCII only for transferring HTML Documents (The scripts are using ASCII by default).

> b)  Everything else - goes Binary (or raw data or all files depending on your program) (Add the word __bin__ in a new line after the server login lines)



Known Issues:
-------------
1)  I ran the batch (.bat) file for accessing remote web server via FTP and downloaded a database file successfully in the native DOS Command prompt.

2)  At first attempt in each computer, it was not successful because Windows Firewall will prompt if to allow this as a private network.  Then repeat the run (.bat) again and it will work.

![Alt text](http://173.0.133.251/download/DOS-Downloaded.gif "Downloaded using DOS prompt")

3)  But when I run in ACL v10, it will not work even after I have allowed it as a private network.  I added "ACL Analytics 10" software into the "list of allowed programs" in the Windows Firewall even and it still do not work.

![Alt text](http://173.0.133.251/download/In-ACL-Not-Downloading-Unless-Firewall-Switched-Off.gif "In ACL Not Downloading Unless Firewall Switched Off")

4)  Finally, I disabled the Windows Firewall altogether and then IT'LL WORK in ACL v10.

![Alt text](http://173.0.133.251/download/Firewall-Off.gif "Firewall Switched Off")


Questions?
----------
Email me: patrickong@gmail.com
