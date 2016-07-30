# 分支sublime
## Sublime Text 3 相关配置文件说明
| 安装好 [sublime text 3](http://www.sublimetext.com/3) 之后
* 配置安放：  
 路径: `C:\Users\Administrator\AppData\Roaming\Sublime Text 3\Packages\User`  
 1.在终端打开 Packages 路径  
 2.删除 User 文件夹  
 3.克隆配置文件  
 4.修改配置文件夹名称为 User

---  

###### 克隆配置文件相关指令：  
**Git Bash :**
```console
cd ~/\AppData/Roaming/Sublime\ Text\ 3/Packages
rm -rf User
git clone -b sublime git@github.com:Blue-Jing/IDE-config.git
mv sublime User
```  
**CMD :**
```console
cd C:\Users\Administrator\AppData\Roaming\Sublime Text 3\Packages
git clone -b sublime git@github.com:Blue-Jing/IDE-config.git
rd /s User
reName sublime User
```  

---  

* 安装插件：  
我所使用的插件包在 [Package Control.sublime-settings 文件](https://github.com/Blue-Jing/IDE-config/blob/sublime/Package%20Control.sublime-settings) 中列出;  
 `Ctrl + ~` 调出 console ，粘贴 [Package Control](https://packagecontrol.io/installation) 下的代码，安装 Package Control 这样所有的包会自动安装上;  
按下 `Ctrl+Shift+P` 调出命令面板，输入并调出 `Install Package` 选项回车，然后在列表中选择要安装的新插件.

