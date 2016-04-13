# tinyImage

A shell script to compress image with pngquant tool in recursive.Thanks to [Kornel](https://github.com/pornel) and his PNG compressor -- [pngquant](https://github.com/pornel/pngquant).

## How to use ?
1. Download the files and put tinyImage and pngquant in you project(or workspace) root directory.
2. Open terminal, switching to the root directory and run the tinyImage shell script. 

``` 
  ./tinyImage
```

## extension
The tinyImage script compress image use command line `pngquant --ext .png --force  -- *.png` at default, you can customize compress style. More detail usage info about `pngquant`, please visit the [GitHub Page](https://github.com/pornel/pngquant)

## issue
when you run the script, the terminal maybe output some error info which like `failed open PNG file ...`, it does not affect the normal use. Because the directory does not have any PNG file, so you can ignore.


# 中文介绍
tinyImage是一个可以将工程目录里面所有的PNG图片进行压缩的一个shell脚本，它使用的是pngquant[https://github.com/pornel/pngquant]压缩工具。

## 实现原理
实现原理非常简单，就是遍历当前目录以及所有子目录，利用pngquant工具批量压缩PNG图片，并且自动替换源文件。

## 如何使用
1. 下载文件，并且将tinyImage和pngquant放在你的工程目录的根目录下；
2. 打开终端，使用cd命令，切换至你的工程根目录下，在终端输入`./tinyImage`运行脚本即可。

## 扩展
tinyImage脚本默认使用的是`pngquant --ext .png --force  -- *.png`，你可以自定义压缩的格式，有关pngquant更多的使用方法，可以查看[pngquant](https://github.com/pornel/pngquant)

## 已知问题
当某个目录没有PNG图片的时候，终端就会输出类似：`failed open PNG file` 的错误，不影响脚本的正常使用，大家可以忽略。

