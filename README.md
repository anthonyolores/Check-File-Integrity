Check File Integrity
=====================

Most of computer user do common file manipulation such as copy, paste, burn, download, upload files, etc. regardless of what operating system they are using. But there are some cases that the process is interrupted and causes the file to be broken. Interruptions happen in different forms like when you are downloading but the internet is disconnected, copying files but the PCs power is unplugged causes of shutting down and many more. `But how to check the integrity of the output file?(file downloaded, uploaded, pasted), well of course you have the original file and output file then compare the two files if same the output file is correct?, It depends. 

There are different ways to compare the original and output file it can be by file size, content, type, name and hash value. Among the different ways hash value is the most efficient and trusted way to validate the correctness of the file. Why? Because it basically compares the unique identity of both files. The unique identity is a piece of data which represents the file it can be extracted using SHA1 or MD5 algorithm. To extract that piece of data we need a 3rd party tool which supports your operating system that implements the algorithm.

###MD5Sum windows tool

MD5Sum is a free windows application that gets the identity of the file using MD5 algorithm. To download this go to http://www.etree.org/md5com.html.

> **Note:** This is only applicable in windows operating system. There might be available tool equivalent for this in other operating system.

###How to Use MD5Sum

 1. Download MD5Sum.exe from http://www.etree.org/md5com.html
 2. Execute  MD5Sum.exe
 3. Open command prompt
 4. Set the current directory where the file is located. In windows `cd "your dir path"`
 5. Enter command  `md5sum "filename.extension"`
 6. It will display the hash value
