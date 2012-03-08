# Peep, a javascript iA Writer-style Markdown WYSIWYG
Meet *peep*, your new friend. [Peep][peep] is attached to a `contenteditable`, and then allows you to input live and lovely Markdown, which is automatically formatted, but still preserves your initial markdown syntax. It tries to replicate [iA Writer's](http://www.iawriter.com/) [Markdown](http://daringfireball.net/projects/markdown/) behavior to the extent *possible* in javascript.

[peep]: http://xn--stf-qla.se/peep/

## Goals
The goal is to replicate the Markdown behavior of iA Writer using web technologies such as HTML5, some heavy javascript and a touch of CSS. That being said, it is not (at least for a start) made to match the Markdown spec, just a small cherry pick of it.

## Dependencies
* jQuery

## Installation
Grab the source from [Peep's GitHub repository](http://github.com/worldeggplant/peep/) and follow the examples. Peep is strict for editing and sends raw Markdown to your server. You will have to install a Markdown parser on your server to display the result to your end users.

## Changelog

v0.2

* **Parses**: footnotes
* **Known bugs**: Editing still doesn't work, selection doesn't work. Ref-style links doesn't work. Basically, What You See Is What You Get, for now, as the previous version.

v0.1

* **Parses** Italic, bold, lists, images, links, blocks, headers
* **Functionality**: The parser *works*, but interaction and contenteditable part remains to be perfected.

## License & copyright
Peep is copyright Jonas Skovmand 2011 and licensed under the MIT license. You can find the full license in the `LICENSE` file.

## Thanks
A big thanks to Stack Overflow's excellent [PageDown](http://code.google.com/p/pagedown/) javascript markdown parser, from which I have borrowed heavily from in creating Peep.