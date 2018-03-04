---
layout: default
header: This is the header variable
---
{% include section.html id=one header="This is the subheading / first section of the page" %}

This is some text.  You can put a lot or a little here.  It doesn't really
matter how much goes here.

    And some code or something

{% include button.html link="/" label="Learn More" %}

Text after a button.  Now we will create a new section:

{% include section.html id=two header="Another section, another subheading" %}

This section of the page can have more text and stuff.  Even a picture:

![test image](https://media.giphy.com/media/28N6C416sUHV3RYqIQ/giphy.gif)

and embed code, too:

<div style="width:100%;height:0;padding-bottom:56%;position:relative;"><iframe src="https://giphy.com/embed/xULW8Fl3U6QWpJlAc0" width="100%" height="100%" style="position:absolute" frameBorder="0" class="giphy-embed" allowFullScreen></iframe></div><p><a href="https://giphy.com/gifs/ugly-americans-xULW8Fl3U6QWpJlAc0">via GIPHY</a></p>

even YouTube:

<iframe width="560" height="315" src="https://www.youtube.com/embed/9CS7j5I6aOc" frameborder="0" allow="autoplay; encrypted-media" allowfullscreen></iframe>

## Markdown headings can be used, but don't generate a new section

And general *markdown* _formatting_ ~~applies~~!

### Including the smaller headings

AND section lines (really, why would you do this to me?)

---

Just like that.

Sections can also forego the headings, if desired:

{% include section.html id=three %}
