# Wonder3D-OneClick

Wonder3D是一个2D图片转3D模型的应用。安装过程比较复杂，我制作了Windows版的一键启动整合包，方便不会安装的人快速上手体验这个应用。



## 整合包使用说明

首先安装Visual Studio 2022，下载链接：[https://visualstudio.microsoft.com/zh-hans/downloads/](https://visualstudio.microsoft.com/zh-hans/downloads/)。勾选使用C++的桌面开发
Visual Studio安装完成后需要将编译工具cl.exe路径添加到系统环境变量path中，

路径为:你的VS2022安装目录\VC\Tools\MSVC\14.42.34433\bin\Hostx64\x64

然后安装12.4或更高版本CUDA

将整合包下载到电脑上解压之后，先运行【下载模型.exe】，我将模型文件上传到了魔塔，会自动从魔塔下载模型文件，然后运行【启动软件.exe】

视频教程：[youtube](https://www.youtube.com/watch?v=-N7HxQ7yXKU)

## 整合包使用注意事项

整合包只支持Windows 10或11 64位系统

软件运行路径中不要有非英文字符和空格

建议电脑英伟达显卡显存6G以上用户体验

使用前请先将英伟达显卡驱动更新到最新版本，否则可能会报错

win11系统运行软件时如果报u2net错误，可将项目文件夹内的u2net文件夹复制到Administrator文件夹内并重命名为.u2net


## Wonder3D整合包下载链接

夸克网盘：[https://pan.quark.cn/s/14825ebdbbc3](https://pan.quark.cn/s/14825ebdbbc3)

百度网盘：[https://pan.baidu.com/s/16kXfAga0kQq7v4nM-15hVw?pwd=28ih](https://pan.baidu.com/s/16kXfAga0kQq7v4nM-15hVw?pwd=28ih)

## Wonder3D链接

[https://github.com/xxlong0/Wonder3D](https://github.com/xxlong0/Wonder3D)

## 其它
微软也开源了一款图片转3D的应用TRELLIS，生成速度更快，而且质量更高。新用户推荐直接体验TRELLIS，TRELLIS一键启动整合包项目链接：https://github.com/aidayang/TRELLIS-OneClick
