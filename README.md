#What Is Osseous?

**Osseous** is a customized version of the amazing [Bones](http://themble.com/bones/) WordPress starter theme by Eddie Machado. I make no bones (pun definitely intended) about it being its own theme; rather, Osseous is just Bones with a few changes and add-ons that I found myself using often. So, instead of making these changes manually each time I start developing a new site, I thought it made sense to include them all from the get go. These changes and additions may or may not be helpful to you.

If you aren't familiar with Bones, use it first before trying out Osseous. Try it out on a simple practice site and get to know how Bones works. Read through all the Bones files - the best part about Bones is the comments and documentation. Customize Bones to your liking and then figure out the best workflow for you.

There are no radical changes here - for the most part, Osseous leaves Bones as-is. Anything that is changed from the original Bones files is labeled with [added by JM]. Where I've supplanted my own styles or code, the original Bones code is commented out so you can always revert back to Bones if you so choose. All of Eddie's original comments are there and I have only added my own when necessary.

#So What Is Different in Osseous?

First, I must note that I exclusively use Sass/SCSS so I have not touched the LESS files at all.

In _normalize.scss:

- margins changed on H1-H6 headings
- margins changed on p, pre
- hyphens turned off globally (I just don't like them for web text :)

In _mixins.scss:

- Flat-UI colors added
- Color Me Sass colors added
- $lucida font stack added
- list-style elements added
- placeholder text mixins
- retina.js mixin for background images
- default buttons changed to flat

In _base.scss

- removed borders on nav elements
- added #logo-mobile {}

In _768up.scss

- removed borders on nav elements
- added #logo-mobile {}
- added body classes
- added .footer {}

In bones.php

- added plugin.js call (commented out)
- uncommented head cleanup items

In functions.php

- added body class functions: page slug, browser, page template
- added thumbnails for excerpt functions
- added highlight search terms function
- dequeue jQuery migrate function

In header.php

- updated title function
- added Open Graph tags for Facebook (commented out)
- added space for web fonts code (Google Web Fonts/TypeKit, etc.)
- changed #logo to be ready for image
- added #logo-mobile div

In scripts.js

- retina.js added

###Other Changes:

- added page-fullwidth.php
- added /library/fonts folder (for custom web fonts)

**Version 1.0**

Customized by Joshua Michaels for BioDesign. <joshua@wearebio.com><br>
[http://wearebio.com/osseous](http://wearebio.com/osseous)


---


# Bones
__A Lightweight Wordpress Development Theme__

Bones is designed to make the life of developers easier. It's built
using HTML5 & has a strong semantic foundation. It was updated recently
using some of the HTML5 Boilerplate's recommended markup and setup.
It's constantly growing so be sure to check back often if you are a
frequent user. I'm always open to contribution. :)

Designed by **Eddie Machado**: http://themble.com/bones

Special Thanks to:
* Paul Irish & the HTML5 Boilerplate
* Yoast for some WP functions & optimization ideas
* Andrew Rogers for code optimization
* David Dellanave for speed & code optimization
* and several other developers. :)

Submit Bugs & or Fixes:
https://github.com/eddiemachado/bones/issues


## License
__[WTFPL](http://sam.zoy.org/wtfpl/)__

	Are You Serious? Yes.


## Meta
* [Changelog](../../blob/master/CHANGELOG.md)
