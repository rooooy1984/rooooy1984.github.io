---
categories: [文章, Blender]
tags: [Blender]
---
### Blender安装第三方Python库（演示库：pillow）

* 进入D:\Program Files\Blender Foundation\blender 2.93\2.93\python\bin（选择你自己的安装路径）
* 在该文件夹地址栏输入 "cmd" 打开控制台
* python.exe -m pip install -i https://pypi.tuna.tsinghua.edu.cn/simple pillow  （清华镜像地址）

> 注意：开头的 "python.exe" 必须有
{: .prompt-tip }

### 以下命令用来检查是否安装成功

* python.exe -m pip list （查看库列表）
* python.exe -m pip show pillow （查看当前pillow库）
