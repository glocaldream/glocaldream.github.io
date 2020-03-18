---
layout: post
title: Color Post
tags: [Test, Color, Markdown] #태그
color: brown #색깔 지정할 수 있음
author: sylhare 
excerpt_separator: <!--more--> # <!--more--> 블로그 목록에서 해당하는 내용을 여기까지만 보여주겠다는 표시
---

# What a colorful post!

This is an idea that came from [xukimseven/HardCandy-Jekyll](https://github.com/xukimseven/HardCandy-Jekyll) 
looking at this cheerful and colorful them, I wanted to enable something similar for mine.

You can go fork and star hers too! 😉

<!--more-->

## How does it work?

Basically you need to add just one thing, the color:

```yml
---
layout: post
title: Color Post
color: brown
---
```

It can either be a html color like `brown` (which look like red to me). Or with the rgb:

```yml
---
layout: post
title: Color Post
color: rgb(165,42,42)
---
```

![computer]( "/assets/img/pexels/computer.jpeg"){:width="100"}

<!-- <img src ="../../../assets/img/pexels/computer.jpeg" width="100%"> -->

The background used is `lineart.png` from [xukimseven](https://github.com/xukimseven) you can edit it in the config file. 
If you want another one, put it in `/assets/img` as well. 
> ⚠️ It's a bit hacking the css in the `post.html`

