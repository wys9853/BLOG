Android Sudio导入github上下载的项目
==================================

将github下载的project中的gradle版本替换为本地的版本
---------
   如果直接将project导入进Android Studio的话，会去下载工程相应版本的gradle，此过程非常慢，有时候还会出现各种错误。
   所以直接使用本地已有的gradle。替换方法很简单，只需要将本地创建的工程中的相应文件夹复制到从github下载的project替换之。
![image](https://github.com/wys9853/BLOG/blob/master/Android%20Study%20notes/image/1.png)

这是我的替换模板
-------------
https://github.com/wys9853/gradle-replacement-template/tree/master
