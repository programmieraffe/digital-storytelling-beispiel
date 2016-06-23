---
title: Introduction article (example)
lang: en
ref: introduction
feature_image: /images/feature_image_introduction_700_300.png
feature_image_alt: 'the title introduction displayed on a green background with some icons'
teaser: 'This article introduces the topic and raises some interesting questions. Check this article if you want to see some markup in action.'
---

This is an introduction article.

**You can find all markdown codes in this cheatsheet: [Open Online Explorer Cheatsheet for markup](https://github.com/MediaLiteracyLab/open-online-explorer/wiki/Cheatsheet-for-article-markup:-links,-images,-videos-&-more)**

Here is an example paragraph:

Lorem ipsum dolor sit amet, consetetur sadipscing elitr, sed diam nonumy eirmod tempor invidunt ut labore et dolore magna aliquyam erat, sed diam voluptua. At vero eos et accusam et justo duo dolores et ea rebum. Stet clita kasd gubergren, no sea takimata sanctus est Lorem ipsum dolor sit amet. Lorem ipsum dolor sit amet, consetetur sadipscing elitr, sed diam nonumy eirmod tempor invidunt ut labore et dolore magna aliquyam erat, sed diam voluptua. At vero eos et accusam et justo duo dolores et ea rebum. Stet clita kasd gubergren, no sea takimata sanctus est Lorem ipsum dolor sit amet.

## Markup and formatting

Formatting is done with [markdown](https://daringfireball.net/projects/markdown/).

### Links

`[I'm an inline-style link to an external page](https://www.google.com)`

Will be rendered to: [I'm an inline-style link to an external page](https://www.google.com)

### Lists

You can create lists:

* list item 1
* list item 2

1. first
2. second

### Images

You can also include images from this repository:

`![alt text]({{ site.github.url }}/images/ "Logo Title Text 1"))`

Images have to be added to the repository first. Please do not forget to provide an alternative text for accessibility!

### Videos

Videos from youtube and vimeo are possible via these commands (see source code in this markdown file):

#### Youtube

{% include youtubePlayer.html id="pF8yJOG_ti8" %}

#### Vimeo

{% include vimeoPlayer.html id="74733097" %}


### License

You can use the [creative commons license chooser](https://creativecommons.org/choose/) and include the html in the article (see article in editor for code):

{% include license.html code='<a rel="license" href="http://creativecommons.org/licenses/by/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by/4.0/88x31.png" /></a>This work is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by/4.0/">Creative Commons Attribution 4.0 International License</a>.' %}
