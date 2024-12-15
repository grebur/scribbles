plugins:
  - jekyll-include-cache
title: Scribbles GitHub Pages
description: This webpage is work in progress.
#remote_theme: mmistakes/minimal-mistakes
#minimal_mistakes_skin: air
permalink: pretty
encoding: "utf-8"
locale: "sv-SE"
timezone: Europe/Stockholm

lsearch: true
lunr:
  search_within_pages: true

paginate: 5 # amount of posts to show
paginate_path: /page:num/

defaults:
  - scope:
      type: pages
      path: ""
    values:
      layout: single
  - scope:
      type: posts
      path: ""
    values:
      layout: single
      author_profile: false
      show_date: true
      read_time: true
      comments: false
      share: false
      related: true