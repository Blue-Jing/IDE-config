# WebStorm 个性化配置
### 安装目录：
>路径：`D:\Program Files (x86)\JetBrains\WebStorm 2016.2\bin`
* `WebStorm64.exe.vmoptions` **64 位 vm配置文件**  
　
* `WebStorm.exe.vmoptions` **32 位 vm配置文件**  
　
* `idea.properties` **属性配置文件**  

### 设置目录：
>路径： `C:\Users\Administrator\.WebStorm2016.2` 
* `config` **个性配置目录 :**  
记录：IDE 主要配置功能、自定义的代码模板、自定义的文件模板、自定义的快捷键、 tasks 记录等.  
　
* `system` **系统文件目录 :**  
包含：缓存、索引、容器文件输出等.  

---
### 配置文件说明：
![个性化配置](https://github.com/Blue-Jing/IDE-config/blob/JetBrains/ws_img/configure-directory-introduce.png)  

> **vm配置文件 :** `WebStorm.exe.vmoptions`   
* 可以根据 jconsole 这类工具观察后进行个性化调整.  

> **属性配置文件 :** `idea.properties`   
* `idea.config.path=${user.home}/.IntelliJIdea/config`  
用于指向 WebStorm 的个性化配置目录，需要注意这里用的是___正斜杠___，默认是被注释.
* `idea.system.path=${user.home}/.IntelliJIdea/system`  
用于指向 WebStorm 的系统文件目录，需要注意这里用的是___正斜杠___，默认是被注释.
* `idea.max.intellisense.filesize=2500`  
用于提高在编辑大文件时候的代码帮助.
