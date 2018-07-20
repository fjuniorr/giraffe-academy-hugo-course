---
title: "Hello Word"
date: 2018-07-19T12:07:59-03:00
draft: false
tags: ["english"]
---

Hello Word!!

{{ range .Site.Taxonomies.languages.english }}
    // in here we can access the page’s information
    {{ .Title }}
    {{ .Description }}
{{ end }}