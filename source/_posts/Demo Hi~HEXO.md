---
title: Demo Hi~HEXO
date: 2017-09-13 20:04:10
description: "Hexo blog Demo Test page 입니다."
tags: [Demo, test, start]
categories: test
toc: true
---

## Quick Start

Welcome to [Hexo](https://hexo.io/)! This is your very first post. Check [documentation](https://hexo.io/docs/) for more info. If you get any problems when using Hexo, you can find the answer in [troubleshooting](https://hexo.io/docs/troubleshooting.html) or you can ask me on [GitHub](https://github.com/hexojs/hexo/issues).


### Create a new post

``` bash
$ hexo new "My New Post"
```

More info: [Writing](https://hexo.io/docs/writing.html)

### Run server

``` bash
$ hexo server
```

More info: [Server](https://hexo.io/docs/server.html)

### Generate static files

``` bash
$ hexo generate
```

More info: [Generating](https://hexo.io/docs/generating.html)


### Deploy to remote sites

``` bash
$ hexo deploy
```

More info: [Deployment](https://hexo.io/docs/deployment.html)

### Alias Generate & Deploy (My Customizing)

``` bash
$ npm run git-up
$ npm run deploy
$ npm run git-pull
```

### 들여쓰기 Tests (list-tab)
> 
- test1
	- **test2** 
    	- test3
>
* Item 1
  * *Item 1a*
  * Item 1b
>
1. Item 1
1. Item 2
1. Item 3
   1. Item 3a
   1. Item 3b



## Using Gist code & embed 

### Gist > 
```js
//code
{% gist chan48/ec4c9293a5e14b88a7778692c3e64c56 %}

//embed
<script src="https://gist.github.com/chan48/ec4c9293a5e14b88a7778692c3e64c56.js"></script>
```
#### Example > 
{% gist chan48/ec4c9293a5e14b88a7778692c3e64c56 %}

### CodePen > 
```js
//mk code
{% codepen ch9|anonymous|anon slugHash theme [defaultTab [height [width]]] %}

//html code
<p data-height="265" data-theme-id="0" data-slug-hash="RLPyzJ" data-default-tab="html,result" data-user="ch9" data-embed-version="2" data-pen-title="Das Video-Element" class="codepen">See the Pen <a href="https://codepen.io/ch9/pen/RLPyzJ/">Das Video-Element</a> by chan (<a href="https://codepen.io/ch9">@ch9</a>) on <a href="https://codepen.io">CodePen</a>.</p>
<script async src="https://production-assets.codepen.io/assets/embed/ei.js"></script>
```
---
#### Example > 

<p data-height="600" data-theme-id="0" data-slug-hash="RLPyzJ" data-default-tab="html,result" data-user="ch9" data-embed-version="2" data-pen-title="Das Video-Element" class="codepen">See the Pen <a href="https://codepen.io/ch9/pen/RLPyzJ/">Das Video-Element</a> by chan (<a href="https://codepen.io/ch9">@ch9</a>) on <a href="https://codepen.io">CodePen</a>.</p>
<script async src="https://production-assets.codepen.io/assets/embed/ei.js"></script>



