# vim 安装 C/C++ 自动补全

## 安装vim
### 安装powervim
```powershell
git clone https://github.com/youngyangyang04/PowerVim.git
cd PowerVim
sh install.sh
```
### powerVim的操作

> 正常模式下的快捷键（非插入模式）
> - ;n &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;// 打开文件目录树显示在屏幕左侧
> - ;m&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;// 打开当前函数和变量目录树显示在屏幕右侧
> - ;h&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;// 光标移动到左窗口
> - ;l&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;// 光标移动到右窗口
> - ;k&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;// 光标移动到上窗口
> - ;j&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;// 光标移动到下窗口 以上四个快捷键特别是打开多个窗口情况下。使用这个快捷键组合非常实用
> - ;w&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;// 保存文件
> - ;u&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;// 向上翻半屏
> - ;d&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;// 向下翻半屏
> - ;1&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;// 光标快速移动到行首
> - ;2&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;// 光标快速移动到行末
> - ;a&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;// 快速切换.h和cpp文件，写C++的时候很方便
> - ;e&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;// 打开一个新文件
> - ;z&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;// 切回shell交互命令，输入fg在切回vim，非常实用
> - ;s&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;// 水平分屏，并打开文件目录选取想打开的文件，如果想新建文件 ，;e 就好
> - ;v&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;// 竖直分屏，并打开文件目录选取想打开的文件，如果想新建文件 ，;e 就好
> - ;fw&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;// 查找项目内关键字，前提是你的系统已经按照了ACK
> - ;ff&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;// 查找项目内文件名
> - ;gt&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;// 跳转到变量或者函数定义的地方，前提是安装ctags，并且在在PowerVim输入 
> - ;tg&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;命令 Jump to - the definition of the keyword where the cursor is located, but make sure you have make ctags
> - ;gr&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;// 跳回，对应着;gt
> - ;tg&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;// 对当前目录打ctag
> - ;y&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;// 保存当前选中的目录到系统剪切板，前提是vim支持系统剪切板的寄存器
> - ;gg&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;// 按顺序光标跳转各个窗口
> - - 一下快捷键是不用;的，直接在 非插入模式 下输入
> - e&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;// 快速删除光标所在的词
> - tabc&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;// 关闭当前tab，可以用:tabnew来打开一个新的tab Close tab, of course you should :tabnew a - file first.
> - F1&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;// 编译并运行C++文件，自己写的C++例子的时候一键编译。前提手 动在当前目录建一个bin文件夹，这是用来存放编译产生的执行文件
> - F1&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;// 编译Java文件
> - F2&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;// 运行Java编译的class文件，一般如果要编译并运行Java文件 按F1编译，在按F2运行
> - gc&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;// 快速注释选中的块（是visual模式下选中的块）
> - gcc&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;// 快速当前行
> - { &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;// 光标向上移动一个代码块
> - } &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;// 光标向下移动一个代码块
> - di(&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;// 删除括号里的内容
> - di{&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;// 删除花括号里的内容

### YouCompleteMe

```powershell
mkdir ~/.vim
cd ~/.vim
git clone https://github.com/ckelsel/vim-init.git
cp ~/.vim/vim-init/.vimrc ~
```
启动vim ```PlugInstall```

安装YCM
```powershell
mkdir ~/.vim
cd ~/.vim
git clone https://github.com/ckelsel/vim-init.git
cp ~/.vim/vim-init/.vimrc ~
```
# Markdown
<iframe src="//player.bilibili.com/player.html?aid=327623069&bvid=BV1JA411h7Gw&cid=171385214&page=1" scrolling="no" border="0" frameborder="no" framespacing="0" allowfullscreen="true"> </iframe>

![](picture/IMG_0183(20221101-200727).JPG)
![](picture/IMG_0184(20221101-200731).JPG)
![](picture/IMG_0185(20221101-200734).JPG)
![](picture/IMG_0186(20221101-200741).JPG)
![](picture/IMG_0187(20221101-200744).JPG)
![](picture/IMG_0188(20221101-200749).JPG)
![](picture/IMG_0189(20221101-200752).JPG)
![](picture/IMG_0190(20221101-200756).JPG)
![](picture/IMG_0190(20221101-200756).JPG)
![](picture/IMG_0191(20221101-200759).JPG)
![](picture/IMG_0192(20221101-200803).JPG)