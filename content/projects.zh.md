---
title: '作品項目'
# date: 2024-05-19
type: landing
# 请参阅 https://bootstrap.hugoblox.com/blocks/portfolio/  
# 此部分显示来自 `content/project/` 的内容。

design:
  # Section spacing
  spacing: '5rem'

# Page sections
sections:
  - block: collection
    content:
      title: 分析机构科研成果及影响
      text: '采用UTD计量法量化贡献比例，**实证**分析科研成果及影响，做具前瞻的系统决策，如科研经费、人员等的投入产出。'
      # 要显示的页面类型。例如：project。
      filters:
        folders:
          - project
        # Only show content with these tags
        tag: 'NetBib'
      sort_by: 'Date'
      sort_ascending: false
    design:
      view: masonry
      fill_image: true
      background: {}
      spacing: {padding: [4px, 0, 4px, 0]}
  - block: collection
    content:
      title: 淨零经济及产业路线
      text: '利用**产业经济**及**能源排放数据**等实证可视化，分析产业投入及产出及排放影响，做具战略的系统思考。'
      # 要显示的页面类型。例如：project。
      filters:
        folders:
          - project
          - vis
        # Only show content with these tags
        tag: 'NetZero'
      sort_by: 'Date'
      sort_ascending: false
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
> 利用實證可視化，分析科研成果及影響，做具前瞻戰略的系統思考. 
{.note} 
      filter_button:
      buttons:
        - name: All
          tag: '*'
        - name: Deep Learning
          tag: Deep Learning
        - name: Other
          tag: Demo
