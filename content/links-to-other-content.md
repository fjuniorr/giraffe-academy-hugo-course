---
title: "Links to Other Content"
date: 2018-07-19T12:08:53-03:00
draft: false
---

There are multiple ways to link to other content, internal or external.

## Internal content

A link using `relref` to [`content/hello-word.md`]({{< relref "hello-word.md" >}})

A link using relative path to [`content/hello-word.md`](hello-word.md) gives 404 page not found error.

A link using relative path to [`content/hello-word.md`](/hello-word.md) gives 404 page not found error.

A link using relative path to [`content/hello-word.md`](/hello-word) works.

## External content

[External link with tooltip](http://dansheffler.com/archive/ "Help text")