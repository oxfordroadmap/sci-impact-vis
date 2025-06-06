---
title: '作品集'
#type: landing
# 请参阅 https://bootstrap.hugoblox.com/blocks/portfolio/  
# 此部分显示来自 `content/project/` 的内容。

sections:
  - block: portfolio
    id: projects
    # 要显示的页面类型。例如：project。
    content:
      title: 分析科研成果及影响
      subtitle: '利用实证可视化，分析科研成果及影响，做具前瞻战略的系统思考'
      text: Add any **markdown** formatted content here - text, images, videos, galleries - and even HTML code!
      filters:
        # Folders to display content from
        folders:
          - project
        # Only show content with these tags
        tags: []
        # Exclude content with these tags
        exclude_tags: []
        # Which Hugo page kinds to show (https://gohugo.io/templates/section-templates/#page-kinds)
        kinds:
          - page

      # Field to sort by, such as Date or Title
      sort_by: 'Date'
      sort_ascending: false

      # 要移除工具栏，请删除整个 `filter_button` 块。
      default_button_index: 0
      # 过滤器工具栏（可选）。
      # 根据需要添加或删除任意数量的过滤器（`filter_button` 实例）。
      # 要显示所有项目，请将 `tag` 设置为 "*"。
      # 要按特定标签过滤，请将 `tag` 设置为现有标签名称。
      # filter_button:
      buttons:
        - name: All
          tag: '*'
        - name: Deep Learning
          tag: Deep Learning
        - name: Other
          tag: Demo
    design:
      # See Page Builder docs for all section customization options.
      # Choose how many columns the section has. Valid values: '1' or '2'.
      columns: '2'
      # Choose a listing view
      view: masonry 
      # view: showcase
      # For Showcase view, flip alternate rows?
      # flip_alt_rows: true
      background: {}
      spacing: {padding: [4px, 0, 4px, 0]}
---

利用实证可视化，分析科研成果及影响，做具前瞻战略的系统思考
