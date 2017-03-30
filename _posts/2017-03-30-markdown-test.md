---

layout: post title: 제목입니다. description: "Just about everything you'll need to style in the theme: headings, paragraphs, blockquotes, tables, code blocks, and more." modified: 2017-03-30 tags: [태그1, 태그2] categories: [카테고리1, 카테고리2] image: feature: 파일명.확장자 credit: 이미지 하단에 나오는 이름

creditlink: 클릭했을 때 URL
---------------------------

여기다가 내용을 작성하면 설명이 나옵니다.

Heading 1
=========

Heading 2
---------

### Heading 3

#### Heading 4

##### Heading 5

###### Heading 6

### Body text 일반 적당한 글씨 크기

Lorem ipsum dolor sit amet, test link adipiscing elit. **굵게나온다.**. Nullam dignissim convallis est. Quisque aliquam.

![Smithsonian Image]({{ site.url }}/images/3953273590_704e3899d5_m.jpg) {: .image-right}

*기울임*. Donec faucibus. Nunc iaculis suscipit dui. 53 = 125. Water is H<sub>2</sub>O. Nam sit amet sem. Aliquam libero nisi, imperdiet at, tincidunt nec, gravida vehicula, nisl. The New York Times <cite>(That’s a citation)</cite>. <u>밑줄쫙</u>. Maecenas ornare tortor. Donec sed tellus eget sapien fringilla nonummy. Mauris a ante. Suspendisse quam sem, consequat at, commodo vitae, feugiat in, nunc. Morbi imperdiet augue quis tellus.

HTML and <abbr title="cascading stylesheets">CSS<abbr> are our tools. Mauris a ante. Suspendisse quam sem, consequat at, commodo vitae, feugiat in, nunc. Morbi imperdiet augue quis tellus. Praesent mattis, massa quis luctus fermentum, turpis mi volutpat justo, eu volutpat enim diam eget metus.

If you want to show just a part of your post in the come page, add the `회색배경에 글씨` tag to your post content. Everything after this tag will be hidden from the page listing page.

### Blockquotes

> 명언같은거 이렇게 쓰면됨

대제목
------

### 숫자 리스트

1.	리스트
	1.	리리스트
	2.	리리스트
	3.	리리스트
2.	리스트

### 점박이 리스트

-	리스트
-	리스트
-	리스트

Tables
------

| Header1 | Header2 | Header3 |
|:--------|:-------:|--------:|
| cell1   |  cell2  |   cell3 |
| cell4   |  cell5  |   cell6 |
| ----    |         |         |
| cell1   |  cell2  |   cell3 |
| cell4   |  cell5  |   cell6 |
| =====   |         |         |
| Foot1   |  Foot2  |   Foot3 |

\{: rules="groups"}

##우왕 코드 스타일이당

설명 대충때려넣고

// CSS {% highlight css %} #container { float: left; margin: 0 -240px 0 0; width: 100%; } {% endhighlight %}

// Console <div id="awesome"> <p>This is great isn't it?</p> </div>

{% highlight html %}<a href="#" class="btn btn-success">Success Button</a> {% endhighlight %}

버튼 만들어서 뭐하리
--------------------

Make any link standout more when applying the `.btn` class.

<div markdown="0"><a href="#" class="btn">Primary Button</a></div>
<div markdown="0"><a href="#" class="btn btn-success">Success Button</a></div>
<div markdown="0"><a href="#" class="btn btn-warning">Warning Button</a></div>
<div markdown="0"><a href="#" class="btn btn-danger">Danger Button</a></div>
<div markdown="0"><a href="#" class="btn btn-info">Info Button</a></div>

Post Featured Image
-------------------

To show an image banner at top of your post, use add the following code:

{% highlight yaml %} image: feature: <name of the image> credit: <source of the image - optional> creditlink: <source of the image (url) - optional> {% endhighlight %}

The image must be in the `/images` folder.
