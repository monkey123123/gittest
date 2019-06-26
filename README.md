# gittest
#可用的rtsp demo，测试管用:
https://github.com/ldm520/android_mediacodec_rtsp_h264

安卓教程，非常详细：
http://www.runoob.com/w3cnote/android-tutorial-listview-item.html
https://developer.android.google.cn/ndk

sendEmail_demo是163邮箱给qq邮箱发邮件的demo。

https://www.imooc.com/video/6206 参见慕课网5-1
c语言,制作静态库或生产静态库的方法：
.o文件和.c文件同时编译的方法：
gcc -c max.c -o max.o ,
gcc max.o hello.c //此时会生成a.out可执行文件。使用./a.out执行，即可输出结果。
如果有.h头文件，则头文件在.c文件里#include "max.h"一下即可，不需要在gcc编译命令里写max.h。

编写makefile的方法
第一行 写总编译指令，
总编译指令需要的依赖文件都在下面写就行了
其实makefile文件只需要看第一行总编译指令就可以了
makefile写好之后，打开shell执行make命令，即可编译出a.out文件。
makefile最好的教程，一看就会，(已验证):
https://www.cnblogs.com/warren-wong/p/3979270.html

做一个nginx+keepalived的双机热备实验：参考：
https://www.cnblogs.com/kaituorensheng/p/4889268.html

fescar生成undolog方法参考：
https://www.jianshu.com/p/74cc4619c674

openssl查看rsa pem格式秘钥对的方法：
私钥：openssl rsa -in privatekey.pem -text
公钥：openssl rsa -pubin -in publickey.pem -text
