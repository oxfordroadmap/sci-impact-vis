---
title: '🤓洞察丶👍推荐丶🧠认知站'
type: landing
# type: landing i.e. pages that can consist of content _blocks_, such as 
cascade:
  - _target:
      kind: page
      #kind: `home`, `page`, `section`, `taxonomy`, or `term` see ## PAGE  https://gohugo.io/quick-reference/glossary/#page-kind 
    params:
      show_breadcrumb: true
sections:
  - block: collection
    id: '🤓洞察'
    content:
      title: '🤓洞察'
      subtitle: '🤓洞察'
      text: '🤓洞察....'
      filters:
        tag: '洞察'
      order: desc
    design:
      view: date-title-summary
      # view: card
      # Choose how many pages you would like to display (0 = all pages)
      count: 2
  - block: collection
    id: '👍推荐'
    content:
      title: '👍推荐'
      page_type: project
      # count: 3
      # Filter on criteria
      filters:
        tag: '推荐'
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
        tag: '认知站'
    design:
      view: date-title-summary
      spacing:
        padding: [0, 0, 0, 0]
  - block: collection
    id: '📚参考文献'
    content:
      title: '📚参考文献'
      filters:
        publication_type: "book"
        # https://docs.citationstyles.org/en/stable/specification.html#appendix-iii-types
        tag: '参考文献'
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