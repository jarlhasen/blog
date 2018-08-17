---
title: 利用 Python 和 OpenCV 写一个自动给博客文章创建特色图片
key: py0818
tags: 
 - Python
 - openCV
 - 图片处理
 - 中文
toc: true
---

![pn](https://ws3.sinaimg.cn/large/006tNbRwgy1fudcrqrir6j30rs06tjs7.jpg)

## 问题描述:

虽然有人喜欢首页是纯文本的博客,当然这样的好处就是可以大大提高博客首页的打开速度,但是至于我这样一个“臭美”的博主来说,这是完全无法忍受的,我希望博客首页,尤其是每一个博文都有一个特色图片,而且由于我自己的强迫症很大,希望每一张图片大小都一样,或者至少图片在视觉上是剧中显示的.(其实 Markdown 是没有所谓的居中这么一个语法规则的,如果希望在 markdown 里面实现居中,那么只能通过 HTML 标签来实现)	

## 开始实现: 

1. 新建一个 GitHub  仓库,命名为 [blog-pic-unite](https://github.com/yaakovazat/blog-pic-unite)
2. 将 GitHub 仓库克隆到本地项目: 

```bash
git clone https://github.com/yaakovazat/blog-pic-unite	
```

3. 进入本地的项目目录:

```bash
cd blog-pic-unite	
```

4. 为项目创建一个虚拟环境:

> 需要事先安装好 Python3 !	

```bash
pyvenv venv venv #在项目根目录创建一个叫 venv 的虚拟环境(Python3)
```

5. 开始编写 Python 代码:

```python
#这里是主函数部分
import cv2

```



