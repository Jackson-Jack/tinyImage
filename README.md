# tinyImage

A shell script to compress the all images of workspace.

## How to use ?
1. Download the files and put tinyImage and pngquant in you project(or workspace) root directory.
2. Open terminal, switching to the root directory and run the tinyImage shell script. 

``` 
  ./tinyImage
```

## extension
The tinyImage script compress image use command line `pngquant --ext .png --force  -- *.png` at default, you can customize compress style. More detail usage info about `pngquant`, please visit the [GitHub Page](https://github.com/pornel/pngquant)


## Special thanks to
* [pngquant](https://github.com/pornel/pngquant)：Lossy PNG compressor — pngquant command and libimagequant library <https://pngquant.org>

# 中文介绍
tinyImage是一个可以将工程目录里面所有的PNG图片进行压缩的一个shell脚本。

## 实现原理
实现原理非常简单，就是查找当前目录以及所有子目录的图片文件，利用pngquant工具批量压缩，并且自动替换源图片。

## 如何使用
1. 下载文件，并且将tinyImage和pngquant放在你的工程目录的根目录下；
2. 打开终端，使用cd命令，切换至你的工程根目录下，在终端输入`./tinyImage`运行脚本即可。

## 扩展
tinyImage脚本默认使用的是`pngquant --ext .png --force  -- *.png`，你可以自定义压缩的格式，有关pngquant更多的使用方法，可以查看[pngquant](https://github.com/pornel/pngquant)

## 特别感谢
* [pngquant](https://github.com/pornel/pngquant)：Lossy PNG compressor

