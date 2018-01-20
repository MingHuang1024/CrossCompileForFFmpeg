这是一个对FFmpeg源码进行裁剪并交叉编译的脚本，目标是编译出能在android上运行的so文件，经裁剪后只支持将MP4转换为gif文件的功能，其它功能则不支持。

脚本中的本地路径要根据实际的NDK所在位置和FFmpeg源码所在位置进行替换。

更详细的介绍请看博客：[Android录屏并利用FFmpeg转换成gif（二） 交叉编译FFmpeg源码](http://blog.csdn.net/MingHuang2017/article/details/79112682)
