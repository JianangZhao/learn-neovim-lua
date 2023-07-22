# NeoVim安装配置

LazyVim

参考[🛠️ Installation | LazyVim](https://www.lazyvim.org/installation)

```bash
git clone https://github.com/LazyVim/starter ~/.config/nvim
```

在windows机器下

```cmd
# 跳转到当前目录下
C:\Users\zhaoj\.config\nvim

# 拷贝lua文件夹 和 init.lua 文件到
C:\Users\zhaoj\AppData\Local\nvim
```

安装neovim

```bash
#打开网址
https://github.com/neovim/neovim/releases/

#找到windows的nvim
https://github.com/neovim/neovim/releases/download/v0.9.1/nvim-win64.msi

#安装
```



```cmd
#拉取配置
git clone https://github.com/VisualGMQ/my-nvim-config.git

#创建路径：C:\Users\zhaoj\AppData\Local\nvim

#将init.lua 和 lua文件夹  copy到C:\Users\zhaoj\AppData\Local\nvim

```



启动nvim

![](.\pics\lazy vim Help page.png)

```bash
#在cmd 或者 windows下的git bash 窗口下 输入 nvm 回车 就会进入lazy vim
nvm

#根据上图的提示在大写模式下 输入对应的按键 H I U S X C L R P D ? 可以进入不同的功能选项


#默认情况使用SPACE 空格作为操作命令的Leader 就是先按下Leader键 在按下其他按键 实现快捷操作
Space + E : 打开文件树
Space + ` : 切换不同的buffer 可以理解为工作窗口
h : 光标向左移动
l : 光标向右移动
j : 光标向下移动
k : 光标向上移动
2k : 光标向上移动到相对当前行的第二行 数字可以是任意当前文档的行数
2l : 光标向下移动到相对当前行的第二行 数字可以是任意当前文档的行数
space + space : 搜索文件
space + | : 向右拆分一个新窗口 拆分的窗口时当前窗口的复制
Shift + ; : 打开CMD line 窗口

```

