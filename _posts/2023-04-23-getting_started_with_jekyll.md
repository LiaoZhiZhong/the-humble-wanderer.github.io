---
title: "Getting started with Jekyll"
---

[First, learn to structure your pages](https://jekyllrb.com/docs/pages/)

[Then learn to structure your posts](https://jekyllrb.com/docs/posts/) 

[Filters and tags](https://jekyllrb.com/docs/liquid/)

[How to fix categories](https://github.com/mmistakes/minimal-mistakes/issues/1764#issuecomment-408850465)

[Adding emojis](https://github.com/jekyll/jemoji)
- I can add emojis by using `:<name>:` :smile:!

[To link to an internal post](https://stackoverflow.com/questions/4629675/jekyll-markdown-internal-links), use the following syntax:
{% raw %}
`[link to internal file]({{ site.baseurl }}{% link _posts/<file_path>.md %})`
{% endraw %}
