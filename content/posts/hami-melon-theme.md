+++
title = "写了个编辑器主题"
date = 2024-10-10
[taxonomies]
categories = ["Coding"]
tags = []
[extra]
+++

*差生文具多，又来折腾编辑器了。*

大学接触到 VSCode 时用的主题一直是 One Dark Pro，
当时觉得非常好看，每天写代码感觉赏心悦目的，现在再看感觉这个主题的配色有点太鲜艳，已经不太喜欢了（但是这个主题的对比度确实很好）。
还用过一段时间的 Tokyo Night，也是最开始很喜欢，用了一段时候后就腻了。
后面一直在用的主题是 Eva，Dark 和 Light 的配色都感觉还好，虽然也很鲜艳就是了...

最近一直在体验 Zed，非常喜欢，它的 UI 也很简洁，不过官方的主题都是拼色的设计，第三方的主题也没有特别满意的，就想着要不自己写一个。
说是写，其实是改，因为定义一个编辑器主题的元素非常多，有些不太知道是啥，完全自己去调每一个颜色过于琐碎，不太现实。

这个主题基于官方的 One 主题修改而来。灵感主要来自于一款叫 [Vesper](https://github.com/raunofreiberg/vesper) 的主题，
它只有两个强调色，其余元素通过颜色的深浅和字体的样式（斜体、粗体等）来做区分，感觉非常有格调。

主题取名 Hami Melon（哈密瓜），主要强调色是绿色和橙色。绿色主要用在 function / method 上，橙色主要用在 type / enum / constructor 上，
keyword 颜色稍微暗淡一点，variable、number、operator 颜色稍重一些以作强调，string 用斜体做视觉上的区分，光标和搜索用了单独的蓝色来做区分，
用到的绿色和橙色同时也是 Git 的新增和修改的标识颜色，还有一些有的没的的颜色也都凭感觉调整了一下。

截图：

![screenshot-light](/assets/hami-theme-screenshot-light.png)

![screenshot-dark](/assets/hami-theme-screenshot-dark.png)

GitHub Repo: <https://github.com/isunjn/hami-melon-zed>

已经发布到 Zed Extension，搜索 Hami Melon 即可。

还有一些细节不太完美，打算自己先用上一段时间，然后把色板再调整一下，到时候有时间也做个同款的 VSCode 主题、Terminal 主题啥的。
