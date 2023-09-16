# 移动端调试利器：Objection

* 最新版本：`v1.0.0`
* 更新时间：`20230916`

## 简介

整理移动端调试利器，用Objection调试Android和iOS的程序。先是Objection的概览；然后是初始化开发环境；接着介绍通用逻辑，包括查看子命令的参数、hook函数的参数；然后是如何调试Android，主要包括android各种子命令，包括hooking、intent；而hooking下面有子命令list、watch、search；list下有子命令class_methods、class_method、services、activities、class_loaders；intent有子命令launch_activity；以及memory的各种子命令，包括search、dump；然后是调试iOS；以及常见问题，包括调试安卓的；最后给出附录，包括语法help、教程和资料。

## 源码+浏览+下载

本书的各种源码、在线浏览地址、多种格式文件下载如下：

### HonKit源码

* [crifan/mobile_reverse_debug_objection: 移动端调试利器：Objection](https://github.com/crifan/mobile_reverse_debug_objection)

#### 如何使用此HonKit源码去生成发布为电子书

详见：[crifan/honkit_template: demo how to use crifan honkit template and demo](https://github.com/crifan/honkit_template)

### 在线浏览

* [移动端调试利器：Objection book.crifan.org](https://book.crifan.org/books/mobile_reverse_debug_objection/website/)
* [移动端调试利器：Objection crifan.github.io](https://crifan.github.io/mobile_reverse_debug_objection/website/)

### 离线下载阅读

* [移动端调试利器：Objection PDF](https://book.crifan.org/books/mobile_reverse_debug_objection/pdf/mobile_reverse_debug_objection.pdf)
* [移动端调试利器：Objection ePub](https://book.crifan.org/books/mobile_reverse_debug_objection/epub/mobile_reverse_debug_objection.epub)
* [移动端调试利器：Objection Mobi](https://book.crifan.org/books/mobile_reverse_debug_objection/mobi/mobile_reverse_debug_objection.mobi)

## 版权和用途说明

此电子书教程的全部内容，如无特别说明，均为本人原创。其中部分内容参考自网络，均已备注了出处。如发现有侵权，请通过邮箱联系我 `admin 艾特 crifan.com`，我会尽快删除。谢谢合作。

各种技术类教程，仅作为学习和研究使用。请勿用于任何非法用途。如有非法用途，均与本人无关。

## 鸣谢

感谢我的老婆**陈雪**的包容理解和悉心照料，才使得我`crifan`有更多精力去专注技术专研和整理归纳出这些电子书和技术教程，特此鸣谢。

## 其他

### 作者的其他电子书

本人`crifan`还写了其他`150+`本电子书教程，感兴趣可移步至：

[crifan/crifan_ebook_readme: Crifan的电子书的使用说明](https://github.com/crifan/crifan_ebook_readme)

### 关于作者

关于作者更多介绍，详见：

[关于CrifanLi李茂 – 在路上](https://www.crifan.org/about/)
