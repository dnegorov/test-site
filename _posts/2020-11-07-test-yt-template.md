---
layout: post
title: Template 21
categories: qwerty # post article tech music life
tags: youtube tech temp fb21
published: true
excerpt_separator: <!--cut-->
fb_picture: /assets/templates/fb/cd-box-1200x628.png # full path to preview picture for social media: Facebook (1200x628px or 476x249px)
fb_picture_width: 1200
fb_picture_height: 628
description: Short description of article in 10 words
---

![alt]({{site.url }}{{ site.baseurl }}{{ page.fb_picture }})

## Text before cut

page name: {{ page.title }}

page address: {{ site.url }}{{ site.baseurl }}{{ page.url }}

<!--cut-->

## Text after cut


### Table

| column 0 | column 1 | column 2 |
| -------: | :------: | :------- |
|    row 1 |  data 1  | data 2   |

  <div class="fb-share-button" data-href="{{site.url}}{{ site.baseurl }}{{ page.url }}" data-layout="button_count"
    data-size="small"><a target="_blank"
      href="https://www.facebook.com/sharer/sharer.php?u={{site.url}}{{ site.baseurl }}{{ page.url }}&amp;src=sdkpreparse"
      class="fb-xfbml-parse-ignore">Поделиться</a></div>

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
