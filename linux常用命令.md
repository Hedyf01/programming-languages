* 查看一个文件夹or文件的大小：`du -sh filename`

-s 表示summary，如果不加，会显示这个文件夹下各个文件的大小
-h 表示hummer readable，就是以kb，gb这种格式


* 机器之间同步文件夹，不包括某个文件： `rsync -avz --exclude 不包括的文件 source destination`

* ssh的服务器后台运行某个进程，希望不受断连影响：  `nohup linux_command > logfile 2>&1 &`

