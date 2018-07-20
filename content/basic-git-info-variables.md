---
title: "Basic Git Info Variables"
date: 2018-07-20T17:30:39-03:00
draft: false
---

We can use the `.GitInfo` object to add status update on every single page. In order to get something like this on every page

![Image](/status-update-info-last-commit.PNG) 
<!-- Note that the path must begin with / for the image to work properly -->

We've added the following html code

```{html}
<div style="color:grey; font-size:12px;">

<p>Last update by {{ .GitInfo.AuthorName }} on {{ .GitInfo.AuthorDate }}</p>
<p><a href="https://github.com/fjuniorr/giraffe-academy-hugo-course/commit/{{.GitInfo.Hash}}" target="_blank">{{ .GitInfo.Subject }}</a></p>

</div>
```

to the `themes/ga-hugo-theme/layouts/_default/single.html` file.

# References

[HUGO Docs on Git Info Variables](https://gohugo.io/variables/git/)