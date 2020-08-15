# 超强vim配置文件

#### 不建议在虚拟机下使用

### 第一种安装方法：

打开终端，执行下面的命令就自动安装好了：
```sh
wget -qO- https://github.com/Hantingsheng/Vim/setup.sh | sh -x
```

### 第二种安装方法(适用于任意Linux系统)：

将 `setup.sh` 下载到 `桌面`，在终端中定位到桌面目录后输入
```sh
sudo bash setup.sh
```
就自动安装好了.

### 第三种安装方法(以Ubuntu为例)：

- 打开终端

- 安装 vim：
```sh
sudo apt-get install vim
```

- 安装ctags：
```sh
sudo apt-get install ctags
```

- 安装一些必备程序：
```sh
sudo apt-get install xclip vim-gnome astyle python-setuptools
```

- python代码格式化工具：
```sh
sudo easy_install -ZU autopep8
```

- 输入：
```sh
sudo ln -s /usr/bin/ctags /usr/local/bin/ctags
```

- clone配置文件：
```sh
cd ~/ && git clone git://github.com/ma6174/vim.git
```

- 输入：
```sh
mv ~/vim ~/.vim
```

- 输入：
```sh
mv ~/.vim/.vimrc ~/
```

- clone bundle 程序：
```sh
git clone https://github.com/gmarik/vundle.git ~/.vim/bundle/vundle
```

- 打开vim并执行bundle程序: 
```sh
:BundleInstall
```

- 重新打开 vim 即可看到效果
