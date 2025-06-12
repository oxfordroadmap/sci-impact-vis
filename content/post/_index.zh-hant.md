---
title: '🤓洞察、👍推薦、🧠認知站'
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
      title: '🤓洞察'
      filters:
        folders:
          - post
        tags:
          - '🤓Insights'
    design:
      view: article-grid
      columns: 2
---

<!-- [🧱 Build your pages with blocks: no-code required! | Hugo Blox Docs](https://docs.hugoblox.com/getting-started/page-builder/#listing-view) -->
<style>
article.prose > h1 {
  font-size: 1.25rem;
  font-weight: 700;
}
</style>