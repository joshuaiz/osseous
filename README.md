#What Is Osseous?

**Osseous** is a customized version of the amazing [Bones](http://themble.com/bones/) WordPress starter theme by Eddie Machado. I make no bones (pun definitely intended) about it being its own theme; rather, Osseous is just Bones with a few changes and add-ons that I found myself using often. So, instead of making these changes manually each time I start developing a new site, I thought it made sense to include them all from the get go. These changes and additions may or may not be helpful to you.

If you aren't familiar with Bones, use it first before trying out Osseous. Try it out on a simple practice site and get to know how Bones works. Read through all the Bones files - the best part about Bones is the comments and documentation. Customize Bones to your liking and then figure out the best workflow for you.

There are no radical changes here - for the most part, Osseous leaves Bones as-is. Anything that is changed from the original Bones files is labeled with [added by JM]. Where I've supplanted my own styles, the original Bones styles are commented out so you can always revert to those styles if you so choose. All of Eddie's original comments are there and I have only added my own when necessary.

#So What Is Different?

First, I must note that I exclusively use Sass/SCSS so I have not touched the LESS files at all.

In _normalize.scss:

- margins changed on H1-H6 headings
- margins changed on p, pre
- hyphens turned off globally

In _mixins.scss:

- Flat-UI colors added
- Color Me Sass colors added
- $lucida font stack added
- list-style elements added
- placeholder text mixins
- retina.js mixin for background images
- default buttons changed
