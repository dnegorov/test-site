---
layout: post
title: Template
categories: tmplt # post article tech music life
tags: youtube tech temp fb4
published: true
excerpt_separator: <!--cut-->
fb_picture: /assets/templates/fb/pencil.png
---

![alt]({{site.baseurl }}{{ site.baseurl }}/assets/templates/cd-box.svg)

## Text before cut

page name: {{ page.title }}

page address: {{ site.url }}{{ site.baseurl }}{{ page.url }}

<!--cut-->

## Text after cut


### Table

| column 0 | column 1 | column 2 |
| -------: | :------: | :------- |
|    row 1 |  data 1  | data 2   |

<div class="fb-share-button" data-href="{{site.url}}{{ page.url }}" data-layout="button_count" data-size="small"><a target="_blank" href="https://www.facebook.com/sharer/sharer.php?u{{site.url}}{{ page.url }}&amp;src=sdkpreparse" class="fb-xfbml-parse-ignore">Поделиться</a></div>

<details>
<summary markdown="span">First level collapsible item</summary>
**Lorem ipsum dolor sit amet...**
</details>

YouTube video
{: .color-red}



<svg style="width: 100px; fill: red;">
    <use xmlns:xlink="http://www.w3.org/1999/xlink" xlink:href="{{ site.baseurl }}/assets/youtube_icon.svg#youtube">
    </use>
</svg>

---

<style>
.color-red {
  color: red;
}
.color-green {
  color: red;
}
.color-blue {
  color: blue;
}

.aligned-right {
    text-align: right;
}
.aligned-left {
    text-align: left;
}
.aligned-center {
    text-align: center;
}
</style>
