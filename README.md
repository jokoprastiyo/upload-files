PHP Upload Files Multipart
============

This is one way to upload files into a directory from the computer.
--------------
Edit and change the following line if the file type invalid
--------------
    if ((($_FILES["file"]["type"] == "pdf") || ($_FILES["file"]["type"] == "text/plain") || ($_FILES["file"]["type"] == "image/png") || ($_FILES["file"]["type"] == "image/jpg") || ($_FILES["file"]["type"] == "image/jpeg") || ($_FILES["file"]["type"] == "image/gif"))) {
---------------
All files and scripts under licenses GNU GP L v2 or later
