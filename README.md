# Doccms-Execute-Code
---
Doccms 2016.05.17 upload_model() in /admini/controllers/system/managemodel.php in Doccms 2016.05.17 allows remote attackers to execute arbitrary PHP code through module management files.
Add webshell to ZIP file and upload ZIP file then getshell.


+ find managemodel
![avatar](https://github.com/SuperSalsa20/Doccms-Execute-Code/blob/master/pic1.png)

+ /admini/controllers/system/managemodel.php: upload file to /tmp and unzip
![avatar](https://github.com/SuperSalsa20/Doccms-Execute-Code/blob/master/pic2.png)


+ includ /inc/class.upload.php:Define the path to upload files /upload+/tmp ==> /upload/tmp/,Define the types of files that can be uploaded
(gif|jpg|jpeg|bmp|png|rar|zip|swf|wma|rm|mp3)
![avatar](https://github.com/SuperSalsa20/Doccms-Execute-Code/blob/master/pic3.png)
![avatar](https://github.com/SuperSalsa20/Doccms-Execute-Code/blob/master/pic4.png)


+ upload zip includ webshell
![avatar](https://github.com/SuperSalsa20/Doccms-Execute-Code/blob/master/pic5.png)


+ getshell
![avatar](https://github.com/SuperSalsa20/Doccms-Execute-Code/blob/master/pic6.png)
![avatar](https://github.com/SuperSalsa20/Doccms-Execute-Code/blob/master/pic7.png)
