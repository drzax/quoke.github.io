# Quoke

A website that showcases quotations and web typography etc.

To submit your own favourite quotation please fork this repo and make a pull request with your html file added to the `_quotations` directory. Make the file look like this:

```html
---
layout: quote
title: Every book is a quotation
date: 2018-05-19
text: Every book is a quotation; and every house is a quotation out of all forests, and mines, and stone quarries; and every man is a quotation from all his ancestors.
author: Ralph Waldo Emerson
size: short
tags: featured
---
<style>
  div.every-book-is-a-quotation {
    font-weight: bold;
    font-size: 22px;
    background-color: aquamarine;
    color: crimson;
    padding: 5em 15px 5.2em;
    text-align: center;
  }

  div.every-book-is-a-quotation div.inner-text {
    max-width: 960px;
    margin: auto;
  }

  @media (min-width: 992px) {
    div.every-book-is-a-quotation {
      font-size: 48px;
    }
  }
</style>

<div class="every-book-is-a-quotation">
  <div class="inner-text">
    "Every book is a quotation; and every house is a quotation out of all forests, and mines, and stone quarries; and every man
    is a quotation from all his ancestors."
    <small>&mdash;Ralph Waldo Emerson</small>
  </div>
</div>
```

If your quote is accepted it will be merged into the repo and it will appear on the site.

Thanks!
