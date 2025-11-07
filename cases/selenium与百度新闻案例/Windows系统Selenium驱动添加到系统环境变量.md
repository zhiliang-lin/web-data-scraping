# Windows系统Selenium驱动添加到系统环境变量

- **前提**：下载好chrome/Edge/FireFox浏览器以及相应的驱动压缩包（三个选一个即可）并解压



![image-20241206151119215](C:\Users\Administrator\AppData\Roaming\Typora\typora-user-images\image-20241206151119215.png)

## 步骤1：复制驱动所在文件夹的文件路径

![image-20241206151551052](C:\Users\Administrator\AppData\Roaming\Typora\typora-user-images\image-20241206151551052.png)

## 步骤2：将路径添加到系统环境变量

在Windows操作系统中将路径添加到系统环境变量的步骤如下：

### 1. 开始菜单搜索环境变量

- 在windows【开始菜单】（快捷键：win + S）搜索“环境变量”

![image-20241206151822596](C:\Users\Administrator\AppData\Roaming\Typora\typora-user-images\image-20241206151822596.png)



### 2. 打开“环境变量”设置

- 在“系统属性”窗口中，点击底部的“环境变量”按钮。

![image-20241206151852609](C:\Users\Administrator\AppData\Roaming\Typora\typora-user-images\image-20241206151852609.png)



### 3. 编辑系统环境变量

- 在“环境变量”窗口中，选择下方的“**系统变量**”部分。
- 找到并选中名为 **`Path`** 的变量，点击“**编辑**”。



![image-20241206152035911](C:\Users\Administrator\AppData\Roaming\Typora\typora-user-images\image-20241206152035911.png)

### 4. 添加新的路径

- 在“编辑环境变量”窗口中，点击“**新建**”。
- 输入你想要添加之前复制的路径。
- 点击“确定”。

![image-20241206152147761](C:\Users\Administrator\AppData\Roaming\Typora\typora-user-images\image-20241206152147761.png)

### 5. 完成

- **关闭所有窗口，确保保存更改。**重新启动命令提示符或其他相关程序以使新路径生效。

这样，你就成功将路径添加到系统环境变量中，可以在任何目录下运行该路径下的程序。