---
layout: post
title:  "What do I think of pre-compiling CSS?"
date:   2017-11-17 13:09:45 +0100
categories: jekyll update
---

Css processors makes it easier to write and maintain css code by adding much needed functionalities. There are a number of different Css processors out there but this site is built using Sass with the scss syntax. Scss is similar to regular css which makes it easier for beginners.

Some added functionalities include: variables, imports, mixins and math!

Here's an example:

```
// variable
$color-light-blue: #add8e6;
$nav-height: 60px;

.nav {
  position: fixed;
  top: 0;
  width: (100%/3);
  height: $nav-height;
}
 
.text-light-blue {color:$color-light-blue;}
.button-light-blue{background:$color-light-blue;}
```

You can even divide your code into multiple files because in the end it all compiles down to a single css file.

The problem with Css processors is that it adds another layer to your site. It needs to rewrite the css file everytime you make a change, and though similar to css, you need to learn another syntax to get your site up and running.