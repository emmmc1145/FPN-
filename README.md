# FPN-
这是一个为Fake pod nano开发的播放器，完全由deepseek开发支持MP3
和flac格式，支持封面显示，滚动歌词，亮度调节，断电记忆等功能
本固件无陀螺仪相关功能
tf卡目录结构
/music/            递归扫描，播放 .mp3 / .flac 
/fonts/*.bin       中文点阵字体；只装一个，放多个时取字号最大的那个
/playlist.txt      扫描生成的曲目清单 + 标签
/.art/NNNNNNNN.rgb 扫描期算好的 460×460 RGB565 封面，文件名是路径哈希
