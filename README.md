# HITSZ-FileSystem
借鉴EXT2结构的基于FUSE架构的小型文件系统

将一个逻辑块分为**超级块**、**索引节点位图**、**数据块位图**、**索引节点**、**数据块**五个部分

实现了基本的ls、mv、touch、mkdir、vim、cat、rm、rm -r等命令，能够满足基本的增删改查操作
