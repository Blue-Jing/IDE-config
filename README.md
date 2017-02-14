# 分支 JetBrains
## WebStorm 相关配置文件说明
* [**部分菜单图文说明**](https://github.com/Blue-Jing/IDE-config/tree/JetBrains/ws_img)  
 
* [**WebStorm 个性化配置**](https://github.com/Blue-Jing/IDE-config/blob/JetBrains/Other-instructions/configure-directory-introduce.md)

* **配置文件 ：**[Jing-settings.jar](https://raw.githubusercontent.com/Blue-Jing/IDE-config/JetBrains/Jing-settings.jar)  

* **Crack文件 ：**[JetbrainsCrack-2.5.6.jar](https://raw.githubusercontent.com/Blue-Jing/IDE-config/JetBrains/JetbrainsCrack-2.5.6.jar)  

---
##### 导入配置文件
>File -> Export Settings 导出  
File -> Import Settings 导入  
导入配置 ：将 [Jing-settings.jar](https://raw.githubusercontent.com/Blue-Jing/IDE-config/JetBrains/Jing-settings.jar) 文件导入即可~  

---
##### Crack文件说明
>1. 将 [JetbrainsCrack-2.6.2.jar](https://github.com/Blue-Jing/IDE-config/blob/JetBrains/JetbrainsCrack-2.6.2.jar) 下载到 `D:\Program Files (x86)\JetBrains\WebStorm 2016.2\bin` 目录下;  
2. 编辑 WebStorm 安装目录下 bin 文件夹中的 `WebStorm.exe.vmoptions` 与 `WebStorm64.exe.vmoptions` 文件;  
3. 在文件头部加上:  
 `-javaagent:D:\Program Files (x86)\JetBrains\WebStorm 2016.2\bin\JetbrainsCrack-2.5.3.jar` ;  
**[ -javaagent: 后面跟的是你刚才存放补丁所在的绝对路径 ]**  
4. 运行 WebStorm 随便输入点什么就可以运行了  

---
##### 推荐插件安装
>File -> Settings -> Pligins 插件列表( `Ctrl+Alt+S` )  
点击 Browse Repositories 输入插件关键字 `搜索-下载-安装`   

![Screenshot](https://github.com/Blue-Jing/IDE-config/blob/JetBrains/ws_img/WS-Plug_in_unit.png)  

---
##### SCSS监听配置
>File -> Settings -> Tools -> File Watchers 监听列表  
把SCSS源文件与生成后的(CSS和map)文件分开目录，则如下设置：  
**Arguments :**  
`--no-cache --update --sourcemap --watch $FileName$:$FileParentDir$\css\$FileNameWithoutExtension$.css`  
**Output paths to refresh :**  
`$FileNameWithoutExtension$.css:$FileNameWithoutExtension$.css.map`  
  
![Screenshot](https://github.com/Blue-Jing/IDE-config/blob/JetBrains/ws_img/SCSS-monitor_cue.png)  
![Screenshot](https://github.com/Blue-Jing/IDE-config/blob/JetBrains/ws_img/SCSS-monitor_config.png)  
