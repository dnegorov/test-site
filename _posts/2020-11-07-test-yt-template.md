---
layout: post
title: Template
categories: post # post article tech music life
tags: youtube
published: true
excerpt_separator: <!--cut-->
---

<svg style="width: 100px; fill: red;">
    <use xmlns:xlink="http://www.w3.org/1999/xlink" xlink:href="{{ site.baseurl }}/assets/youtube_icon.svg#youtube">
    </use>
</svg>

## Text before cut

<!--cut-->

## Text after cut

![Image]({{ site.baseurl }}/assets/2020-11-07-test-yt-template/pm.jpg)

### Table

| column 0 | column 1 | column 2 |
| -------: | :------: | :------- |
|    row 1 |  data 1  | data 2   |


<details>
<summary markdown="span">First level collapsible item</summary>
**Lorem ipsum dolor sit amet...**
</details>

YouTube video
{: .color-red}

<iframe style="width: 100%; height: 20rem" src="https://www.youtube.com/embed/6ZwjdGSqO0k" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

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
