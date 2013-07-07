Download and Upload via FTP
=========================================

This script lets you connect via FTP to remote server to download and upload files.


1)  Downloading is handled by these 2 files (Use Notepad to edit their source and target drive and folder locations and the filename to download)

a)  download.bat

b)  download.ftp


2)  Uploading is handled by these 2 files (Use Notepad to edit their source and target drive and folder locations and the filename to upload)

a)  upload.bat

b)  upload.ftp


Note:
-----
The above includes a "live" connection to a web server with a working website.  You may freely use it to test and customise the script for downloading or uploading purposes but please handle it with care by not uploading large files or sensitive / illegal materials.


Known Issues:

1)  I ran the batch (.bat) file for accessing remote web server via FTP and downloaded a database file successfully in the native DOS Command prompt.

2)  At first attempt in each computer, it was not successful because Windows Firewall will prompt if to allow this as a private network.  Then repeat the run (.bat) again and it will work.

3)  But when I run in ACL v10, it will not work even after I have allowed it as a private network.  I added "ACL Analytics 10" software into the "list of allowed programs" in the Windows Firewall even and it still do not work.

4)  Finally, I disabled the Windows Firewall altogether and then IT'LL WORK in ACL v10.



Email me if you found some solution to the above or have any questions: patrickong@gmail.com
