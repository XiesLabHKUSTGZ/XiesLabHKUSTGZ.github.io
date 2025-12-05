---
title: People
date: 2022-10-24

type: landing

sections:
  - block: people
    content:
      title: Meet the Team
      # Choose which groups/teams of users to display.
      #   Edit `user_groups` in each user's profile to add them to one or more of these groups.
      user_groups:
          - Professors
          - PhD Students
          - Graduate Students
          - Undergraduate Students
          - Research Assistants
          - Visitors
          - Alumnus
      sort_by: Params.grade
      sort_ascending: false  # -23 (2023) 在 -24 (2024) 前面（降序排列）
    design:
      show_interests: false
      show_role: true
      show_social: true
      # People block 使用 view 参数控制布局
      # view: grid  # 使用网格布局
      # # CSS 类来控制每行显示数量
      # css_class: people-grid-3
---