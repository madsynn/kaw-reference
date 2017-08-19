---
layout: page
title: Acronyms
---

<div class="form-group col-sm-6">
  <label>Acronym Search:</label>
  <input type="text" id="myInput" onkeyup="myFunction()" placeholder="Search for names..">
  <small>type in possible keywords for you search and watch them magically appear</small>
</div>

{% include acrobat.md %}

## Table

<table>

<tbody>

<tr>

<th>Table Header 1</th>

<th>Table Header 2</th>

<th>Table Header 3</th>

</tr>

<tr>

<td>Division 1</td>

<td>Division 2</td>

<td>Division 3</td>

</tr>

<tr class="even">

<td>Division 1</td>

<td>Division 2</td>

<td>Division 3</td>

</tr>

<tr>

<td>Division 1</td>

<td>Division 2</td>

<td>Division 3</td>

</tr>

</tbody>

</table>

* * *

## Preformatted Text

Typographically, preformatted text is not the same thing as code. Sometimes, a faithful execution of the text requires preformatted text that may not have anything to do with code. Most browsers use Courier and that’s a good default — with one slight adjustment, Courier 10 Pitch over regular Courier for Linux users.

### Code

Code can be presented inline, like `<?php bloginfo('stylesheet_url'); ?>`, or within a `<pre>` block.

CSS code

```css
#container {
    float: left;
    margin: 0 -240px 0 0;
    width: 100%;
}
```

Ruby code

```ruby
class Song
  def initialize(title, artist, album)
    @title  = name
    @artist = artist
    @album  = album
  end
end

class InstrumentalSong < Song
  def initialize(name, artist, album, lyrics)
    super(name, artist, album)
    @lyrics = lyrics
  end
end
```

## Blockquotes

Let’s keep it simple. Italics are good to help set it off from the body text. Be sure to style the citation.

> Good afternoon, gentlemen. I am a HAL 9000 computer. I became operational at the H.A.L. plant in Urbana, Illinois on the 12th of January 1992\. My instructor was Mr. Langley, and he taught me to sing a song. If you’d like to hear it I can sing it for you. <cite>— [HAL 9000](http://en.wikipedia.org/wiki/HAL_9000)</cite>

And here’s a bit of trailing text.

* * *

## Text-level semantics

The [a element](#) example
The <abbr>abbr element</abbr> and <abbr title="Title text">abbr element with title</abbr> examples
The **b element** example
The <cite>cite element</cite> example
The `code element` example
The <del>del element</del> example
The <dfn>dfn element</dfn> and <dfn title="Title text">dfn element with title</dfn> examples
The _em element_ example
The _i element_ example
The <ins>ins element</ins> example
The <kbd>kbd element</kbd> example
The <mark>mark element</mark> example
The <q>q element <q>inside</q> a q element</q> example
The <s>s element</s> example
The <samp>samp element</samp> example
The <small>small element</small> example
The <span>span element</span> example
The **strong element** example
The <sub>sub element</sub> example
The <sup>sup element</sup> example
The <var>var element</var> example
The <u>u element</u> example

* * *

## Embeds

Sometimes all you want to do is embed a little love from another location and set your post alive.

### Video

Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.

<iframe src="//player.vimeo.com/video/83910533?title=0&amp;byline=0&amp;portrait=0" width="600" height="338" frameborder="0" webkitallowfullscreen="" mozallowfullscreen="" allowfullscreen=""></iframe>

Culpa qui officia deserunt mollit anim id est laborum.

### Slides

Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.

<div><iframe class="speakerdeck-iframe" frameborder="0" src="//speakerdeck.com/player/88f09170c0e60131e0fe72c781b73270?" allowfullscreen="true" mozallowfullscreen="true" webkitallowfullscreen="true" style="border: 0px; margin: 0px; padding: 0px; border-radius: 5px; width: 710px; height: 461.37499999999955px; background: transparent;"></iframe></div>

Culpa qui officia deserunt mollit anim id est laborum.

### Audio

Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.

<iframe width="100%" height="450" scrolling="no" frameborder="no" src="https://w.soundcloud.com/player/?url=https%3A//api.soundcloud.com/tracks/202156472&amp;auto_play=false&amp;hide_related=false&amp;show_comments=true&amp;show_user=true&amp;show_reposts=false&amp;visual=true"></iframe>

Culpa qui officia deserunt mollit anim id est laborum.

### Code

Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt.

<div><iframe id="cp_embed_bcqhe" src="//codepen.io/brenden/embed/VLjKMQ/?height=268&amp;theme-id=0&amp;slug-hash=bcqhe&amp;default-tab=result&amp;user=brenden" scrolling="no" frameborder="0" height="268" allowtransparency="true" allowfullscreen="true" class="cp_embed_iframe undefined" style="width: 100%; overflow: hidden;"></iframe></div>

It is awesome.

<small>Source: Markdown code of this page is based on Ghost's [comprehensive style test](http://demo.ghost.io/style-test/)</small>
