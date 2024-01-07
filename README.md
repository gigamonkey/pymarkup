Python Markup Parser
====================

Markup is a text markup language primarily useful for prose documents such as
books and articles. It is designed to be editable in a plain text editor and to
allow for arbitrary logical markup. The grammar of a Markup file is defined in
terms of a mapping to an abstract syntax tree which can then be rendered into a
number of formats, e.g. HTML, PDF, TeX, RTF, etc.

The basic syntax is similar to Markdown and reStructuredText with a bit of TeX
thrown in for good measure but is designed to be more general than Markdown or
reStructuredText by providing several mechanisms for introducing arbitrary tags.

I have implemented Markup several times in different languages and used it for
for writing all three of my books: _[Practical Common
Lisp](http://www.gigamonkeys.com/book/)_, _[Coders at
Work](http://www.codersatwork.com/)_, and _[The
Grid](https://www.amazon.com/gp/product/B072K1JM33/ref=as_li_tl?ie=UTF8&tag=gigamonkeys-20&camp=1789&creative=9325&linkCode=as2&creativeASIN=B072K1JM33&linkId=a276d7ed7eda8c1d56059b8e07273dca)_.
as well as the essays on my website.

For various reasons I need an implementation of Markup in Python so this is
going to be it.

See also:

* [Monkeylib YAMP](https://github.com/gigamonkey/monkeylib/tree/main/yamp)

* [Haskell implementation using Parsec](https://github.com/gigamonkey/haskell-markup)

* [A Ruby implementation I never used for anything](https://github.com/gigamonkey/markup)

* [Original Common Lisp implementation](https://github.com/gigamonkey/monkeylib-markup)
