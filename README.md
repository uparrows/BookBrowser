This repo is a fork of pgaskin/BookBrowser ，what i've done was translated this repo into chinese ,and fix some js problems. thanks to pgaskin for developing this software.

# 图书库

这是nas端图书管理器BookBrowser的汉化版，由本人将其汉化，并且修复一些js问题，添加一些功能 ,原仓库见：https://github.com/pgaskin/BookBrowser

一个易于使用的工具，用于生成基于 Web 的 ePub 和 PDF 电子书浏览器。您需要做的就是将其下载到您的电子书所在的文件夹中，然后运行它。还有一个演示的功能。


[<img src="https://img.shields.io/docker/pulls/dezhao/bookbrowser_cn.svg">](https://hub.docker.com/r/dezhao/bookbrowser_cn/)


[📄 教程](https://yuanfangblog.xyz/technology/545.html) 

![扫码查看详细](https://user-images.githubusercontent.com/38988286/147882172-cba65035-2b2b-456f-ac0d-a85f867ab892.png)


# 特征

多种书籍格式：epub、pdf、mobi（基本支持）

搜索、高级搜索、搜索任意字段组合、查看结果中的所有信息

列表显示、响应式网页界面、更新通知

浏览方式：作者 系列

排序：最后添加、按字母顺序、基于网络的阅读器

自定义字体、颜色、大小、间距、记住你的阅读位置

图书搜索、使用方便快速、没有额外的依赖

## 截图

![book-desktop](https://user-images.githubusercontent.com/38988286/154711303-3ada9ec4-ae50-4aeb-8a0e-7ad10b42106a.png)
![books-list](https://user-images.githubusercontent.com/38988286/154710906-3b1d5caa-f1d6-4be6-a2fe-07cc069c5625.png)
![authors](https://user-images.githubusercontent.com/38988286/154710639-cccf44f7-7fb8-4c5d-b075-caa9c84bf4e4.png)
![book-mobile](https://user-images.githubusercontent.com/38988286/147832566-72e6db38-20a8-48f3-8ebb-4ea2738e7d45.png)


## 阅读器截图

| 桌面 | 移动 |

| ![reader-desktop](https://user-images.githubusercontent.com/38988286/154710045-f12664e6-abfd-4382-8216-8a86f69df104.png) |![reader-mobile](https://user-images.githubusercontent.com/38988286/147832639-93d2e5f5-4179-4af0-9091-86e1071eb041.png)
 |
 
 ## pdf阅读功能
 ![6](https://user-images.githubusercontent.com/38988286/154708600-0d7c741c-fb91-454e-b03a-2084d318ff1c.png)


## 高级搜索



| ![list-desktop](https://user-images.githubusercontent.com/38988286/147832650-e8a4cb77-59ff-4aa3-ae92-c623e4e2f1da.png)

## 图书下载

![7](https://user-images.githubusercontent.com/38988286/154708929-ab3abafb-804f-4822-a96f-541f3fe0e8f9.png)

## 手机客户端 beta

![12](https://user-images.githubusercontent.com/38988286/154712377-4ba41fd9-bbd4-4321-ad1b-97482266bab2.jpg)


## 系统要求
服务器适用于所有平台。

Web 界面适用于 IE 9+、Edge、Firefox 3+、Chrome、Safari 5.1+、Opera 17+ 和 Android 浏览器 4.4+。

基于网络的阅读器适用于 IE 10+、Edge、Firefox 28+、Chrome 21+、Safari 9+、Opera 17+ 和 Android 浏览器 4.4+。

## 用法

```
Usage: BookBrowser [OPTIONS]

Options:
  -a, --addr string      the address to bind the server to ([IP]:PORT) (default ":8090")
  -b, --bookdir string   the directory to load books from (must exist) (default "/home/patrick/src/BookBrowser")
  -h, --help             Show this help text
  -n, --nocovers         do not index covers
  -t, --tempdir string   the directory to store temp files such as cover thumbnails (created on start, deleted on exit unless already exists) (default "/tmp/bookbrowser946254949")
      --version          Show the version
```
