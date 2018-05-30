---
title: "Nested and mixed lists, modified post"
categories:
  - test
tags:
  - template
  - test
last_modified_at: 2018-05-30T09:00:00-00:00
published: false
---

This is an template demo for post.
Đây là template demo của một bài viết.

## Nested and mixed lists
### Ordered -- Unordered -- Ordered

1. ordered item
2. ordered item
  * **unordered**
  * **unordered**
    1. ordered item
    2. ordered item
3. ordered item
4. ordered item

### Ordered -- Unordered -- Unordered

1. ordered item
2. ordered item
  * **unordered**
  * **unordered**
    * unordered item
    * unordered item
3. ordered item
4. ordered item

### Unordered -- Ordered -- Unordered

* unordered item
* unordered item
  1. ordered
  2. ordered
    * unordered item
    * unordered item
* unordered item
* unordered item

### Unordered -- Unordered -- Ordered

* unordered item
* unordered item
  * unordered
  * unordered
    1. **ordered item**
    2. **ordered item**
* unordered item
* unordered item

### Modified date
This post has been updated and should show a modified date if `last_modified_at` is used in the layout.
Plugins like [**jekyll-sitemap**](https://github.com/jekyll/jekyll-feed) use this field to add a `<lastmod>` tag your `sitemap.xml`.
