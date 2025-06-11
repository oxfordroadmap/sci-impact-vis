---
title: 🤓Insights, 👍Recommendations, 🧠Cognitive Frames
cascade:
  - _target:
      kind: post
    params:
      show_breadcrumb: true
sections:
  - block: collection
    id: 🤓Insights
    content:
      title: 🤓Insights
      filters:
        folders:
          - post
        tags:
	      - _Insights_
    design:
      view: article-grid
      columns: 2
  - block: collection
    id: 👍Recommendations
    content:
      title: 👍Recommendations
      filters:
        folders:
          - post
        tags:
	      - _Recommendations_
    design:
      view: article-grid
      columns: 3
  - block: collection
    id: 🧠Cognitive Frames
    content:
      title: 🧠Cognitive Frames
      filters:
        folders:
          - post
        tags:
	      - _Cognitive Frames_
    design:
      view: article-grid
      columns: 1
---


<!-- [🧱 Build your pages with blocks: no-code required! | Hugo Blox Docs](https://docs.hugoblox.com/getting-started/page-builder/#listing-view) -->