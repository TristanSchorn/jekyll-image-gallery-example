---
layout: gallery
title: A More Complex Example
no_menu_item: true # required only for this example website because of menu construction
support: [jquery, gallery]
---

This example shows how to include several galleries into one page. Also notice that some captions have been set.

{% include gallery-layout-flip.html gallery=site.data.galleries.flip %}

This is an example gallery. All images licensed under [CC-BY-NC-SA license][license]. Check the [Git Repo][repo] for a copy of this license.

[license]: http://creativecommons.org/licenses/by-nc-sa/4.0/
[repo]: https://github.com/tristanschorn/jekyll-gallery-example
