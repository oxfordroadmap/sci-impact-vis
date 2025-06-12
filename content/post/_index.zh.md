---
title: 🤓洞察丶👍推荐丶🧠认知站
type: landing
# type: landing i.e. pages that can consist of content _blocks_, such as 
cascade:
  - _target:
      kind: page
    params:
      show_breadcrumb: true
sections:
  - block: collection
    id: '🤓洞察'
    content:
      title: '🤓Insights'
      subtitle: '🤓洞察'
      text: '🤓洞察....'
      filters:
      # Filter on criteria
      #  author: ""
      #  category: ""
        tags:
          - insights
      #  tag: 'insights'
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
      # view: date-title-summary
      view: card
      # Page type to display. E.g. post, talk, publication...
      page_type: post
      # Choose how many pages you would like to display (0 = all pages)
      count: 2
  - block: collection
    id: '👍推荐'
    content:
      page_type: post
      # count: 3
      # Filter on criteria
      filters:
        tag: '👍推荐'
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
    id: '🧠认知站'
    content:
      title: '🧠认知站'
      filters:
        tags: '🧠Cognitive Frames'
    design:
      view: date-title-summary
      spacing:
        padding: [0, 0, 0, 0]
  - block: collection
    id: '📚References'
    content:
      title: '📚References'
      filters:
        publication_type: "book"
        # https://docs.citationstyles.org/en/stable/specification.html#appendix-iii-types
        tag: '📚References'
    design:
      view: citation
---

<!-- [🧱 Build your pages with blocks: no-code required! | Hugo Blox Docs](https://docs.hugoblox.com/getting-started/page-builder/#listing-view) -->
<style>
article.prose > h1 {
  font-size: 1.25rem;
  font-weight: 700;
}
</style>