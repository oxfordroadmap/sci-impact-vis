---
title: 🤓洞察、👍推薦、🧠認知站
type: landing
# type: landing i.e. pages that can consist of content _blocks_, such as 
cascade:
  - _target:
      kind: page
    params:
      show_breadcrumb: true
sections:
  - block: collection
    id: 🤓洞察
    content:
      title: 🤓洞察
      subtitle: '🤓洞察'
      text: '🤓洞察....'
      # Page type to display. E.g. post, talk, publication...
      page_type: post
      # Choose how many pages you would like to display (0 = all pages)
      count: 2
      # Filter on criteria
      filters:
      #  author: ""
      #  category: ""
        tag: "🤓Insights"
        exclude_featured: false
        exclude_future: false
        exclude_past: false
        publication_type: ""
      # Choose how many pages you would like to offset by
      offset: 0
      # Page order: descending (desc) or ascending (asc) date.
      order: desc
    design:
      # Choose a layout view
      view: date-title-summary
      # view: article-grid
      # columns: 2
      # Reduce spacing
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