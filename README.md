# AA-lib

`AA-lib`是一个可移植的`ASCII`图形加速(GFX)库

[相关资源下载](./download/download.md)

[库文档](./documents/toc.md)

## 在linux系统上安装AA-lib和BB示例

可以直接使用 `sudo apt-cache search aalib`搜索`AA-lib`的已编译包，搜索结果如下：


`pi@raspberrypi:~ $ sudo apt-cache search aalib | grep ASCII`

```
bb - ASCII-art demo based on AAlib
libaa1 - ASCII art library
libaa1-dbg - ASCII art library, debugging symbols
libaa1-dev - ASCII art library, development kit
python-aalib - Python interface to AAlib, an ASCII art library
python3-aalib - Python 3 interface to AAlib, an ASCII art library
```

### 安装并运行

`sudo apt-get install -y libaa1-dev bb && bb`

## 在Mac上安装AA-lib

安装Homebrew

`/usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"`

安装AA-lib

`brew install aalib`

安装BB示例程序



