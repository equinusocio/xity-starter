---
title: A post with embeds and images
date: '2020-01-25'
tags:
  - images
  - content
  - embeds
---

This post contains iframe embedded elements that are wrapped inside a css class to let you to add custom style. Here's an example of a Codepen embed.

<iframe height="500" style="width: 100%;" scrolling="no" title="Border Radius Morphing" src="https://codepen.io/equinusocio/embed/jezBdZ?height=300&theme-id=10535&default-tab=css,result" frameborder="no" allowtransparency="true" allowfullscreen="true">
  See the Pen <a href='https://codepen.io/equinusocio/pen/jezBdZ'>Border Radius Morphing</a> by Mattia Astorino
  (<a href='https://codepen.io/equinusocio'>@equinusocio</a>) on <a href='https://codepen.io'>CodePen</a>.
</iframe>

## Images and pictures

This starter uses a custom transformer to parse `markdown` content and improve it. An example of this are the images. If you add an image with title to your markdown, it will be replaced with a `<picture>` element, and the title is placed as `<figcaption>` in order to keep a basic semantic structure.

**The following image code is:**

`![Alt](https://bit.ly/3aJXGqo 'Sample title')`

![Alt](https://bit.ly/3aJXGqo 'Sample title')