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
        tags:
          - 🤓Insights
    design:
      view: date-title-summary
      columns: 2
  - block: collection
    id: 👍Recommendations
    content:
      page_type: post
      # count: 3
      # Filter on criteria
      filters:
        tag: "👍Recommendations"
        exclude_featured: false
        exclude_future: false
        exclude_past: false
        publication_type: ""
      order: desc
    design:
      view: article-grid
      columns: 3
      # Reduce spacing
      spacing:
        padding: [0, 0, 0, 0]
  - block: collection
    id: 🧠Cognitive Frames
    content:
      page_type: post
      filters:
        tag: "🧠Cognitive Frames"
      order: desc
    design:
      view: article-grid
      columns: 3

  - block: collection
    id: 🧠Cognitive Frames
    content:
      title: 🧠Cognitive Frames
      filters:
        tags:
          - 🧠Cognitive Frames
    design:
      view: date-title-summary
      columns: 1
      spacing:
        padding: [0, 0, 0, 0]
---


<!-- [🧱 Build your pages with blocks: no-code required! | Hugo Blox Docs](https://docs.hugoblox.com/getting-started/page-builder/#listing-view) -->
<style>
article.prose > h1 {
  font-size: 1.25rem;
  font-weight: 700;
}
</style>