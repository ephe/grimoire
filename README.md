# Grimoire

Grimoire is a mobile-friendly d20 SRD 5e spellbook that organizes spell lists by class and level.

See the latest compiled build here: [http://ephe.github.io/grimoire/](http://ephe.github.io/grimoire/)

It's been a while. The Grimoire has been pruned to display only the spells from the d20 5e SRD to provide a hopefully entertaining example of how to use Jekyll to do something weird. Unless you've got typos or bugs to file, please consider this project frozen.

Thank you all for your help over the years! May your games ever be fun and your rolls to your liking :)

## Structure

Spells can be found inside `_posts/`. Each spell gets its own post, written and stored as a [Markdown](http://daringfireball.net/projects/markdown/basics) file. The date is arbitrary and never displayed, but still necessary for [Jekyll](http://jekyllrb.com) to process the posts properly.

If you'd like to help fill out the rest of the spells from the PHB, for each new spell you make:

1. Make a new post inside `_posts/` for each new spell, and copy the formatting from another spell.
2. Submit a pull request for the spell(s) when you're finished, and that's it! Thank you so much. :)

## Build Instructions

I've edited _config.yml for my own build purposes, but if you've got [Jekyll](http://jekyllrb.com) set up locally, the following should create the build from your friendly command line terminal:
`jekyll serve -Vw --no-watch --baseurl ""`

## Thanks

Thanks to @sethxd for suggesting [Jets.js](http://nexts.github.io/Jets.js/), a CSS search engine that plays nicely with Jekyll.

All spells here are offered under the [Open Game License](http://5e.d20srd.org/ogl.htm), but the Grimoire is not affiliated with Wizards of the Coast, Inc.
