# Bilibili_video_to_MP4
使用 Termux 将缓存的 BiliBili视频 转换为 MP4格式

更新系统

    pkg update
    pkg upgrade -y

安装ffmpeg

    pkg install -y ffmpeg
    
下载仓库 ffmpeg_bilibili 文件

[安卓11开始无法访问哔哩哔哩数据使用管理员权限执行]

    tsu

运行脚本 选择文件夹 等待输出
    
    bash ffmpeg_bilibili

