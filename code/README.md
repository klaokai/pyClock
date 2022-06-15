## 代码结构
boot.py ：启动参数配置，可以不用。

main.py：主函数代码

data: 素材

    |---Fonts : 字库文件
	
    |---picture：主题图片素材
	
    |---CityCode.txt：全国城市编码

libs: 项目Micropython库

    |---urllib: urequest库
	
    |---ap.py: AP热点配网
	
    |---global_var.py：全局变量定义

ui：UI主题库 

    |---default.py: 默认主题（图片素材位于“/data/picture/default”目录下）
	
    |---dial.py：极简表盘）
	
    |---photo_album.py：默认主题（图片素材位于“/data/picture/photo_album”目录下）

  （用户可以自定义UI主题并在这里添加，通过主函数按键切换，添加过多主题可能导致内存不足。）



## 版本说明

2022-6-15
1、支持对纯中文或中文、英文、数字混合的WiFi SSID连接。

2022-6-9：v1.0 正式发布。