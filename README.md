# backup_file

作者简介：
#####@Author:shiwei.du
#####@Website:https://www.dushiwei.cn

工具简介：

> linux 和 windows 下支持全量备份和增量备份文件夹，并将备份后的文件进行压缩

1:window下使用说明：
> - win_backup_file.exe  Window下备份目录的执行文件  
> - 行效果如下:   
>  
>     ![第一次运行](https://github.com/dsw0214/backup_file/blob/master/win_backup_first_time.png)
>       ：
>       
>     ![第二次运行](https://github.com/dsw0214/backup_file/blob/master/win_backup_second_time.png)

2:linux下使用说明

>  -  linux_backup_file      linux环境下备份脚本
>  - linux_bakc_file.txt     linux下执行范例

3：参数说明：
> - 第一个提示输入的路径为将要备份的源目录(确保将要备份的目录存在)
> - 第二个提示输入的路径为备份的目标路径(如果此目录不存在脚步会自动创建)
> - 第三个提示输入为备份文件的名称(默认是将要备份的源目录最后一层目录的名称)

 
4:注意事项
> - 输入文件路径的时候请记得输入最后的反斜线
> - 第一次执行备份脚步的话，脚步会自动判断并进行全量备份，并将备份文件压缩后存储在目标路径下
> - 以后如果备份的话确保目标路径和备份文件名称同第一次一致，脚步会进行增量备份源目录文件  
> - 请不要手动删除备份的目录路径下.log文件（除非你不想继续备份文件）
