---
layout: gallery
title: Cityscape
no_menu_item: true # required only for this example website because of menu construction
support: [jquery, gallery]
---

This example shows how to include several galleries into one page. Also notice that some captions have been set.

{% include gallery-layout.html gallery=site.data.galleries.wallpapers %}
