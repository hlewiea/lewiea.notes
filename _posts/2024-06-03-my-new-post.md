--- 
# Front Matter at the top
layout: post
title: TITLE
author: lewiea
date: 2024-06-03 21:33:00 +0800
categories: [Demo-Blogging, test] #  designed to contain up to two elements,
tags: [tag]     # TAG names should always be lowercase, the number of elements in tags can be zero to infinity
description: Short summary of the post.
toc: true # the Table of Contents (TOC) is displayed on the right panel of the post. If you want to turn off TOC for a specific post, add the following to the post’s Front Matter or _config.yml and set the value of variable toc to false to turn it off globally,
comments: true
# media_subpath: /path/to/media/ # to specify the resource path prefix for the current post/page range,
---

## 0.1 image
![Desktop View](/assets/img/sample/images.jpg){: width="700" height="400" .left }
_Image Caption_

![Light mode only](/assets/img/sample/images.jpg){: .light }
![Dark mode only](/assets/img/sample/images.jpg){: .dark .shadow }

## 0.2 video
https://www.bilibili.com/video/BV1Q44y1B7Wf

{% include embed/bilibili.html id='BV1Q44y1B7Wf' %}

## 0.3 other
```shell
echo 'No more line numbers!'
```
{: .nolineno }
