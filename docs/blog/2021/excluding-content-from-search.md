---
template: main.html
description: >
  Three new simple ways to exclude dedicated parts of a document from the search
  index, allowing for more fine-grained control
search:
  exclude: true
---

# Excluding content from search

__The latest Insiders release brings three new simple ways to exclude
dedicated parts of a document from the search index, allowing for more
fine-grained control.__

<aside class="mdx-author" markdown>
![@squidfunk][@squidfunk avatar]

<span>__Martin Donath__ · @squidfunk</span>
<span>
:octicons-calendar-24: September 26, 2021 ·
:octicons-clock-24: 5 min read
</span>
</aside>

  [@squidfunk avatar]: https://avatars.githubusercontent.com/u/932156

---

Two weeks ago, Material for MkDocs Insiders shipped a [brand new search
plugin], yielding [massive improvements in usability], but also in [speed
and size] of the search index. Interestingly, as discussed in the previous
blog article, we only scratched the surface of what's now possible. This
release brings some useful features that enhance the writing experience,
allowing for more fine-grained control of what pages, sections and blocks of a
Markdown file should be indexed by the built-in search functionality.
