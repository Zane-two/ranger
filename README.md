# ranger

![image](https://user-images.githubusercontent.com/104540627/172030647-c9012067-b6d8-4773-bc38-84505a53293b.png)

## 安装必要组件

```
$ sudo apt-get install ranger     # ranger 的主程序
$ sudo apt-get install caca-utils # img2txt 图片
$ sudo apt-get install highlight  # 代码高亮
$ sudo apt-get install atool　    # 存档预览
$ sudo apt-get install w3m        # html页面预览
$ sudo apt-get install poppler    # pdf预览
$ sudo apt-get install mediainfo  # 多媒体文件预览
$ sudo apt-get install catdoc     # doc预览
$ sudo apt-get install docx2txt   # docx预览
$ sudo apt-get install xlsx2csv   # xlsx预览
```

## 配置

ranger默认情况下不会生成配置文件，需要手动生成（拷贝）：
```
ranger --copy-config=all
```

## 用法

```
    1. 方向键和hjkl，用于目录导航
    2. r 文件打开方式
    3. [] 父目录快速跳转
    4. H 历史记录
    5. L 历史记录
    6. zh ^h 隐藏文件
    7. o 排序
    8. / 搜索
    9. S 退出后跳转到退出前的文件夹
    10. yp 复制当前文件路径
    11. yn 复制选定文件名
    12. y. 复制文件名 （.之前部分）
    13. :shell
    14. :mkcd 
    15. cw 重命名文件 
    16. :rename
    17. :bulkrename
    18. v 全部选中
    19. yy 复制,pp 粘贴
    20. po 粘贴并覆盖
    21. dd 剪切
    22. dD 删除
    23. dU 查看当前文件目录大小
    24. w 进入任务管理器
    25. dd 取消任务
    26. ：compress 压缩 自己设置
    27. :extracthere 解压缩 自己设置
    28. ranger --copy-config=all 从etc 中复制配置文件
    29. commands.py 可以自己加指令
    30. rc.conf 主要配置文件，快捷键
    31. rifle.conf 默认打开方式配置
```
