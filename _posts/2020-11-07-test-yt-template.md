---
layout: post
title: Template 22
categories: qwwerty # categories for articles: post article tech music life (/post/music/tech/life/2020-12-12-test-article.html)
tags: youtube tech temp fb22 # Tags cloud
published: true # Post not published in blog if false
excerpt_separator: <!--cut-->
fb_picture: /assets/templates/fb/cd-box-1200x628.png # full path to preview picture for social media: Facebook (1200x628px or 476x249px)
fb_picture_width: 1200 # Image width in pixels: 1200 or 476 for Facebook
fb_picture_height: 628 # Image height in pixels: 628 or 249 for Facebook
description: Article description for social networks. Short review of article or first text block from the beginning. Replace this text for new article.
---
[comment]: # (Start OF POST)
[comment]: # (Start of excerpt block)

[comment]: # (Header image of article. By default the same as preview image for social networks)
![alt]({{site.url }}{{ site.baseurl }}{{ page.fb_picture }})

## Text before cut

page name: {{ page.title }}

page address: {{ site.url }}{{ site.baseurl }}{{ page.url }}

[comment]: # (End of excerpt block)
<!--cut-->

## Text after cut

Text of article here...

## And some elements:

### Table

[comment]: # (Example of table with content alignment. One blanc line before table.)

| column 0 | column 1 | column 2 |
| -------: | :------: | :------- |
|    row 1 |  data 1  | data 2   |

[comment]: # (Example for collapsed block)
<details>
  <summary markdown="span">Collapsible item</summary>
  Text inside collapsible block.
</details>


[comment]: # (CSS Style example)
Red text aligned to center
{: .color-red .aligned-center}

[comment]: # (SVG image with style example)
SVG image here:
<svg style="width: 100px; height: 50px; fill: red;">
    <use xmlns:xlink="http://www.w3.org/1999/xlink" xlink:href="{{ site.baseurl }}/assets/youtube_icon.svg#youtube">
    </use>
</svg>

[comment]: # (YouTube video: Insert as iframe inside div block and remove width and height properties in iframe block)
YouTube video here:
<div class="youtube_container">
  <iframe src="https://www.youtube.com/embed/1QGxFpSb6Sc" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
</div>

---
[comment]: # (END OF POST)

[comment]: # (CSS Styles used in article)
<style>
.youtube_container {
  position: relative;
  width: 100%;
  padding-top: 56.25%; /* 16:9 Aspect Ratio */
}
iframe {
    position: absolute;
    top: 0;
    width: 100%;
    height: 100%;
}
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
