---
title: '作品項目'
# date: 2024-05-19
# type: landing
# 请参阅 https://bootstrap.hugoblox.com/blocks/portfolio/  
# 此部分显示来自 `content/project/` 的内容。

design:
  # Section spacing
  spacing: '5rem'

# Page sections
sections:
  - block: collection
    # 要显示的页面类型。例如：project。
    content:
      title: 分析科研成果及影响
      subtitle: '利用实证可视化，分析科研成果及影响，做具前瞻战略的系统思考'
      text: Add any **markdown** formatted content here - text, images, videos, galleries - and even HTML code!
      filters:
        folders:
          - project
        # Only show content with these tags
        #tags: []
        # Exclude content with these tags
        #exclude_tags: []
        # Field to sort by, such as Date or Title
      sort_by: 'Date'
      sort_ascending: false
      # 要移除工具栏，请删除整个 `filter_button` 块。
      default_button_index: 0
      # 过滤器工具栏（可选）。
      # 根据需要添加或删除任意数量的过滤器（`filter_button` 实例）。
      # 要显示所有项目，请将 `tag` 设置为 "*"。
      # 要按特定标签过滤，请将 `tag` 设置为现有标签名称。
      buttons:
        - name: All
          tag: '*'
        - name: Deep Learning
          tag: Deep Learning
        - name: Other
          tag: Demo
    design:
      # Choose a listing view
      # view: masonry 
      # view: showcase
      # For Showcase view, flip alternate rows?
      # flip_alt_rows: true
      view: article-grid
      fill_image: false
      columns: 3
      background: {}
      spacing: {padding: [4px, 0, 4px, 0]}
---
> 利用实证可视化，分析科研成果及影响，做具前瞻战略的系统思考. 
{.note} 