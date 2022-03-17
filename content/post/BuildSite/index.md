---
title: How I build this Site
subtitle: On this page you will find sources and small explenantion how I made this site.
summary: On this page you will find sources and small explenantion how I made this site.

authors:
- admin

tags:
- Website

categories:
- Website

# Link this post with a project
projects: []

# Date published
date: "2020-12-13T00:00:00Z"

# Date updated
lastmod: "2020-12-13T00:00:00Z"

reading_time: false  # Show estimated reading time?
share: false  # Show social sharing links?
profile: false  # Show author profile?
comments: false  # Show comments?

# Optional header image (relative to `assets/media/` folder).
header:
  caption: ""
  image: ""
---

{{< toc >}}

## Prerequirements

* `git` and Github account
* `Hugo`
* (`R`, RStudio and Blogdown)

## Setup

* [Netfly](https://www.netlify.com/)
{{< youtube LIFvgrRxdt4 >}}

## Make page

[Page Elements: Writing content with Markdown, LaTeX, and Shortcodes](https://wowchemy.com/docs/content/writing-markdown-latex/)

## Google Analytics

```YAML
google_analytics: '3345897419'
```

stream id not measurement id

## Code Highlighting

highlight.js:

* [program languages](https://cdnjs.com/libraries/highlight.js)
* [styles](https://highlightjs.org/static/demo/)

## Jupyter Notebook

```julia
using Pimc

function test(a::Int64, b::Int64)
    if a == 1
        return true
    else
        return false
    end
end
```

 <iframe
       src="./JupyterColorstyle.html"
       width="100%"
       height="500px"
       style="border:none;">
 </iframe>

