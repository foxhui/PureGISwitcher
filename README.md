# PureGISwitcher
纯净的原神官服与B服互切换工具

## 使用
> [!WARNING]
> 请勿将程序放在游戏目录内，否则会导致检查资源完整性时报错，若您的游戏在“Program Files”文件夹中，请以管理员身份运行程序

### 通过Release下载使用（推荐）
单一个exe文件，方便操作
- 通过[Release](https://github.com/foxhui/PureGISwitch/releases)下载`PureGISwithcer.exe`文件，并把文件放在一个空白的文件夹中，同时新建一个`PureGISwicther`文件夹
- 通过[Release](https://github.com/foxhui/PureGISwitch/releases)下载`Plugins_xx.zip`文件，并解压其内容放入上一步创建的`PureGISwicther`文件夹中
- 运行`PureGISwitcher.exe`
- 选择游戏目录和游戏入口（如果需要搭配解帧工具使用，游戏入口则选择解帧工具）
- Enjoy(:

### 通过Niva自行构建
可自行修改
- 通过[Niva](https://bramblex.github.io/niva/)下载Niva DevTools
- 将仓库克隆或下载，导入Niva
- 点击构建
- 通过[Release](https://github.com/foxhui/PureGISwitch/releases)下载`Plugins_xx.zip`文件，并解压其内容放入程序所谓文件夹下的`PureGISwicther`文件夹中
- 运行`PureGISwitcher.exe`
- 选择游戏目录和游戏入口（如果需要搭配解帧工具使用，游戏入口则选择解帧工具）
- Enjoy(:

## 截图
![Screenshot](https://raw.github.com/foxhui/PureGISwitcher/master/screenshot.png)

## 声明
### 文件来源
`Plugins_xx.zip`提取自B服游戏包的`YuanShen_Data/Plugins`文件夹

### 免责声明
本工具原理很简单，只是简单修改`config.ini`和添加或删除`PCGameSDK.dll`文件以及`BLPlatform64`文件夹，并没有对游戏进行注入修改，若您非常顾虑是否使用，请立即停止使用，使用后的后果自负，工具和工具作者不承担任何责任
