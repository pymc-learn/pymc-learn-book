---
interact_link: content/features/citations.ipynb
kernel_name: python3
title: 'Probabilistic Machine Learning for Text And Sequences'
prev_page:
  url: /features/interact
  title: 'Probabilistic Machine Learning for Text And Sequences'
next_page:
  url: /features/search
  title: 'Probabilistic Machine Learning for Text And Sequences'
comment: "***PROGRAMMATICALLY GENERATED, DO NOT EDIT. SEE ORIGINAL FILES IN /content***"
---

# Including citations in your book

Because `jupyter-book` is built on top of Jekyll, we can use the excellent
[jekyll-scholar](https://github.com/inukshuk/jekyll-scholar) book to
include citations and a bibliography with your book.

**Note that this only works if you're building your book HTML locally and
hosting the HTML files online somewhere**. This can still use GitHub pages, but
not the auto-generation of a cite from markdown files feature of GitHub pages.
This is because GitHub pages doesn't include the `jekyll-scholar` plugin.

## How to use citations

Including citations with your markdown files or notebooks is done in the following
way.

1. Modify the file in `_bibliography/references.bib`. This has a few sample citations
in bibtex form. Update as you wish!
2. In your content, add the following text to include a citation
   
   
