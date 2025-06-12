---
title: '🤓Insights, 👍Recommendations, 🧠Cognitive Frames'
type: landing
# type: landing i.e. pages containing _blocks_, such as the **homepage**
cascade:
  - _target:
      kind: page
      #kind: `home`, `page`, `section`, `taxonomy`, or `term` see ## PAGE  https://gohugo.io/quick-reference/glossary/#page-kind 
    params:
      show_breadcrumb: true
sections:
  - block: collection
    id: '🤓Insights'
    content:
      title: '🤓Insights'
      filters:
        tags:
          - insights
    design:
      view: card
  - block: collection
    id: '👍Recommendations'
    content:
      page_type: post
      # count: 3
      # Filter on criteria
      filters:
        tag: recommendations
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
    id: '🧠Cognitive Frames'
    content:
      title: '🧠Cognitive Frames'
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
<!-- [ default views:  article-grid (with columns); card; citation; date-title-summary] (https://github.com/HugoBlox/hugo-blox-builder/tree/44e75541f7be16116e80e5c71ff98f6997d63fe5/modules/blox-tailwind/layouts/partials/views) -->


<style>
article.prose > h1 {
  font-size: 1.25rem;
  font-weight: 700;
}
</style>