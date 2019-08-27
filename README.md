# Doccms-Execute-Code
---
Doccms 2016.05.17 upload_model() in /admini/controllers/system/managemodel.php in Doccms 2016.05.17 allows remote attackers to execute arbitrary PHP code through module management files.
Add webshell to ZIP file and upload ZIP file then getshell.


find managemodel
[pic]


/admini/controllers/system/managemodel.php: upload file to /tmp and unzip
[pic]


includ /inc/class.upload.php:Define the path to upload files /upload+/tmp ==> /upload/tmp/,Define the types of files that can be uploaded
(gif|jpg|jpeg|bmp|png|rar|zip|swf|wma|rm|mp3)
[pic]
[pic]


upload .zip
[pic]


getshell
[pic]
