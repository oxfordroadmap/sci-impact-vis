---
title: 🤓Insights, 👍Recommendations, 🧠Cognitive Frames
type: landing
# type: landing i.e. pages that can consist of content _blocks_, such as the **homepage**
cascade:
  - _target:
      kind: page
      #kind: section see ## PAGE OPTIONS at hogo.yaml
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
          - 🤓Insights
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
          - 👍Recommendations
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
          - 🧠Cognitive Frames
    design:
      view: article-grid
      columns: 1
---


<!-- [🧱 Build your pages with blocks: no-code required! | Hugo Blox Docs](https://docs.hugoblox.com/getting-started/page-builder/#listing-view) -->
<style>
article.prose > h1 {
  font-size: 1.25rem;
  font-weight: 700;
}
</style>