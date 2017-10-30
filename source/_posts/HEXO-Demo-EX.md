---
title: Demo Ex on Hexo 
date: 2017-09-13 20:04:10
description: "Hexo Demo page 입니다."
tags: [Demo-test, start, ref-ex, pin]
categories: 
- test/ref-ex
toc: true
published: true
top: true
---

## Quick Start : Basic
Hexo 블로그 가이드 입니다. 

- HEXO SET-UP
  ![](/images/HEXO-SETUP.png)

### Alias Generate & Deploy (Customized)

``` bash
$ npm start
$ npm run g
...
$ npm run git-up
$ npm run deploy
...
$ npm run git-pull
```

### 들여쓰기 Tests (list-tab)
```language
- test1
	- __test2__ 
    		- test3

* Item 1
  * *Item 1a*
  * Item 1b

1. Item 1
1. Item 2
1. Item 3
   1. Item 3a
   1. Item 3b

```
#### Example >

- test1
	- __test2__ 
    	- test3

* Item 1
  * *Item 1a*
  * Item 1b

1. Item 1
1. Item 2
1. Item 3
   1. Item 3a
   1. Item 3b


## Feature : Insert code, embed & Etc.EX

- - -
### Repl.it >
```js
// embed code
<script src="//repl.it/embed/NJmv/0.js"></script>
```

#### Example >

<script src="//repl.it/embed/NJmv/0.js"></script>

[VisualizeCode](https://goo.gl/fdcT8M)
- - -
### Stackblitz > 
```js
<iframe style="border:none" width="100%" height="650px" src="https://stackblitz.com/edit/react-sb6bgp?embed=1&file=index.js"></iframe>
```

#### Example > 
<iframe style="border:none" width="100%" height="650px" src="https://stackblitz.com/edit/react-sb6bgp?embed=1&file=index.js"></iframe>

- - -
### Contents 접기 (html5) > 
```language
<details>
<summary><strong> 폴딩 (자세한 내용을 보려면 펼쳐주세요)</strong></summary>

contents ~

</details>

```
- - -
#### CodePen > 

```js
//mk code
{% codepen ch9|anonymous|anon slugHash theme [defaultTab [height [width]]] %}

//html code
<p data-height="265" data-theme-id="0" data-slug-hash="RLPyzJ" data-default-tab="html,result" data-user="ch9" data-embed-version="2" data-pen-title="Das Video-Element" class="codepen">See the Pen <a href="https://codepen.io/ch9/pen/RLPyzJ/">Das Video-Element</a> by chan (<a href="https://codepen.io/ch9">@ch9</a>) on <a href="https://codepen.io">CodePen</a>.</p>
<script async src="https://production-assets.codepen.io/assets/embed/ei.js"></script>
```


<details>
<summary><strong> Example > (자세한 내용을 보려면 펼쳐주세요)</strong></summary>

<p data-height="600" data-theme-id="0" data-slug-hash="RLPyzJ" data-default-tab="html,result" data-user="ch9" data-embed-version="2" data-pen-title="Das Video-Element" class="codepen">See the Pen <a href="https://codepen.io/ch9/pen/RLPyzJ/">Das Video-Element</a> by chan (<a href="https://codepen.io/ch9">@ch9</a>) on <a href="https://codepen.io">CodePen</a>.</p>
<script async src="https://production-assets.codepen.io/assets/embed/ei.js"></script>
</details>

- - -

#### SlideShare >
```js
// embed code
<iframe src="//www.slideshare.net/slideshow/embed_code/key/3G6d3GWSW3COF4" width="860" height="485" frameborder="0" marginwidth="0" marginheight="0" scrolling="no" style="border:1px solid #CCC; border-width:1px; margin-bottom:5px; max-width: 100%;" allowfullscreen> </iframe>
```

<details>
<summary><strong> Example > (자세한 내용을 보려면 펼쳐주세요)</strong></summary>

<iframe src="//www.slideshare.net/slideshow/embed_code/key/3G6d3GWSW3COF4" width="860" height="485" frameborder="0" marginwidth="0" marginheight="0" scrolling="no" style="border:1px solid #CCC; border-width:1px; margin-bottom:5px; max-width: 100%;" allowfullscreen> </iframe> 

[AWS 6월 웨비나  AWS CodeStar를 통한 DevOps 기반 프로젝트 운영 (윤석찬 테크에반젤리스트)](https://www.slideshare.net/awskorea/aws-code-star-devops)

</details>

- - -

### Mind42 > 

```js
// embed code
<iframe width='100%' height='760' frameborder='0' src='https://mind42.com/mindmap/58f4458e-3a87-4532-9134-e6e466ed4556?rel=embed'></iframe>
```

#### Example > 

<iframe width='100%' height='760' frameborder='0' src='https://mind42.com/mindmap/58f4458e-3a87-4532-9134-e6e466ed4556?rel=embed'></iframe>

- - -



