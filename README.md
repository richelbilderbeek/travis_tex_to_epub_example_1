# travis_tex_to_epub_example_1

[![Travis CI logo](TravisCI.png)](https://travis-ci.org)

[![Build Status](https://travis-ci.org/richelbilderbeek/travis_tex_to_epub_example_1.svg?branch=master)](https://travis-ci.org/richelbilderbeek/travis_tex_to_epub_example_1)

[travis_tex_to_epub](https://github.com/richelbilderbeek/travis_tex_to_epub) example that converts a TeX (`.tex`) file to EPUB, using Travis CI.

This GitHub is part of [the Travis Tutorial](https://github.com/richelbilderbeek/travis_tutorial)

It shows that using `tex4ebook` is superior over using `pandoc`

## Comparison, when using `pandoc`

Feature|`pandoc`|`tex4ebook`
---|---
TOC|Not shown implicity, but is present in sidebar|Present
Abstract|Absent|Present
Bibliography|Absent|Present
Tables|Not horizontal nor vertical lines, no caption|Shown correctly
Listings|Code is shown in default font, captions absent|monospaced font, captions shown
Figures|PNG can be shown, but not in `figure` environment|PNG can be show, did not test for `figure` environment
Referencing to table or figure|Shows LaTex code|Shows number and hyperlink
Quoting citations|Quotations (`[1]`) not shown|Shown correctly
TikZ|Shows LaTex code|Shown correctly

See the three documents here:

 * [example_pandoc.epub](example_pandoc.epub)
 * [example_tex4ebook.epub](example_tex4ebook.epub)
 * [example.pdf](example.pdf)

## External links

 * [![Build Status](https://travis-ci.org/richelbilderbeek/travis_tex_to_epub.svg?branch=master)](https://travis-ci.org/richelbilderbeek/travis_tex_to_epub) [travis_tex_to_epub](https://github.com/richelbilderbeek/travis_tex_to_epub): overview of examples
