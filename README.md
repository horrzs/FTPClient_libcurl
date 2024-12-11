# FTPClient_libcurl
包含功能为：   
1、向Ftp服务器上传文件   
2、从Ftp服务器下载特定文件  
3、从Ftp某个文件夹里面下载所有文件   
4、远程在FTP服务器指定位置创建文件夹   
5、查看FTP服务器指定目录内所有文件名   
解决了FTP上传/下载文件时，文件名有中文，有特殊字符时无法上传/下载的问题。

libcurl编译方式：见csdn，链接如下：
[http://t.csdnimg.cn/jo3AY](https://blog.csdn.net/yh_secret/article/details/140642789?fromshare=blogdetail&sharetype=blogdetail&sharerId=140642789&sharerefer=PC&sharesource=yh_secret&sharefrom=from_link)

代码使用样例：
见FTP.cpp

// visual studio入门使用技巧:   
//   1. 使用解决方案资源管理器窗口添加/管理文件   
//   2. 使用团队资源管理器窗口连接到源代码管理  
//   3. 使用输出窗口查看生成输出和其他消息  
//   4. 使用错误列表窗口查看错误  
//   5. 转到“项目”>“添加新项”以创建新的代码文件，或转到“项目”>“添加现有项”以将现有代码文件添加到项目  
//   6. 将来，若要再次打开此项目，请转到“文件”>“打开”>“项目”并选择 .sln 文件 
