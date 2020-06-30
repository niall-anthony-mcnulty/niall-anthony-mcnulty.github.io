---
layout: post
title:  "Getting set up on Jupyter Notebook & Python"
date:   2020-05-15
excerpt: "Been wanting to learn Python but don't know how to get set up? This blog piece will walk you through setting up Jupyter Notebook and Python on either Mac or PC. Let your Python adventure begin now!"
tag:
- markdown 
- syntax
- sample
- test
- jekyll
comments: true
---
## Helping noobs get set up in 10 minutes so they can start their Python adventure…

<p align="center">
 ![coderman](/niall-anthony-mcnulty.github.io/assets/img/coderman.jpg){:class="img-responsive"} 
</p>
<br/>
Hello everybody! I hope you are all happy and healthy. If you have found yourself reading this article, it is probably for one of two reasons.

1. You want to learn how to write Python but just don’t know how to get started.
2. You stumbled upon this article, and now you’re thinking to close the tab as this holds no interest over you. But slowly… I’m starting to pique your interest and you have decided, ‘why not, let’s read on. I guess I’m a coder now’.

Funnily enough, I decided to write this article for my mum. Hi Mum. For the past month, I have been writing a ‘Beginners Guide to Python’ with new articles coming out each week. The aim is to help those wanting to start their Python journey. My mum has been following along step by step like the super fan she is. However, she mentioned she couldn’t keep up anymore without a medium to write and execute code on. So voila! This article was born to address that issue.
This article will get us set up on Jupyter Notebook to the point where we can write and execute Python code. It is aimed at beginners and will have step by step instructions, keeping it as simple as possible and with as little technical jargon as possible. Along the way, we will use our Terminals /Cmd, so I will include a mini-tutorial on how to navigate those as well.
For those unfamiliar with Python, it is a popular coding language with uses ranging from web applications, websites, data analytics, data visualisations, web-scraping, robotics, machine learning etc.
Let’s crack on shall we?<br/>
<br/>
<iframe src="https://giphy.com/embed/3orieRSPKRODbLKBPO" width="480" height="366" frameBorder="0" class="giphy-embed" allowFullScreen></iframe><p><a href="https://giphy.com/gifs/season-5-the-simpsons-5x3-3orieRSPKRODbLKBPO">via GIPHY</a></p>

> Lorem ipsum dolor sit amet, test link adipiscing elit. Nullam dignissim convallis est. Quisque aliquam.

## List Types

### Ordered Lists

1. Item one
   1. sub item one
   2. sub item two
   3. sub item three
2. Item two

### Unordered Lists

* Item one
* Item two
* Item three

## Tables

| Header1 | Header2 | Header3 |
|:--------|:-------:|--------:|
| cell1   | cell2   | cell3   |
| cell4   | cell5   | cell6   |
|----
| cell1   | cell2   | cell3   |
| cell4   | cell5   | cell6   |
|=====
| Foot1   | Foot2   | Foot3
{: rules="groups"}

## Code Snippets

{% highlight css %}
#container {
  float: left;
  margin: 0 -240px 0 0;
  width: 100%;
}
{% endhighlight %}

## Buttons

Make any link standout more when applying the `.btn` class.

{% highlight html %}
<a href="#" class="btn btn-success">Success Button</a>
{% endhighlight %}

<div markdown="0"><a href="#" class="btn">Primary Button</a></div>
<div markdown="0"><a href="#" class="btn btn-success">Success Button</a></div>
<div markdown="0"><a href="#" class="btn btn-warning">Warning Button</a></div>
<div markdown="0"><a href="#" class="btn btn-danger">Danger Button</a></div>
<div markdown="0"><a href="#" class="btn btn-info">Info Button</a></div>

## KBD

You can also use `<kbd>` tag for keyboard buttons.

{% highlight html %}
<kbd>W</kbd><kbd>A</kbd><kbd>S</kbd><kbd>D</kbd>
{% endhighlight %}

Press <kbd>W</kbd><kbd>A</kbd><kbd>S</kbd><kbd>D</kbd> to move your car. **Midtown Maddness!!**

## Notices

**Watch out!** You can also add notices by appending `{: .notice}` to a paragraph.
{: .notice}
