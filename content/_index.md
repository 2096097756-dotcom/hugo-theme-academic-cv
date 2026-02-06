---
# Leave the homepage title empty to use the site title
title: ''
summary: ''
date: 2025-02-07
type: landing

design:
  # Default section spacing
  spacing: '6rem'

sections:
  # ────────────────────────────────────────────────────────────
  # 1. 个人档案 (Profile / Bio)
  # ────────────────────────────────────────────────────────────
  - block: resume-biography-3
    content:
      username: me
      text: '' 
      # button:
      #   text: Download CV
      #   url: uploads/resume.pdf
    design:
      background:
        gradient_mesh:
          enable: true
      name:
        size: md
      avatar:
        size: medium
        shape: circle

  # ────────────────────────────────────────────────────────────
  # 2. 教育背景与技能 (Education & Skills)
  # ────────────────────────────────────────────────────────────
  - block: markdown
    id:education
    content:
      title: '🎓 Education & Skills'
      subtitle: ''
      text: |-
        ### **Education**
        
        *   **2025.09 - Present**: Undergraduate Student, **School of the Gifted Young (SCGY)**, University of Science and Technology of China (**USTC**).
            *   **GPA**: 4.15 / 4.30 (Avg: 93.21)
            *   **Major**: Physics (Intended)
        *   **2023.09 - 2025.06**: High School Student, Hefei No.1 High School.

        ### **Skills**
        
        *   **Languages**: Chinese (Native), English (Learning)
        *   **Programming**: C/C++ (Basic)
        
    design:
      columns: '2'

  # ────────────────────────────────────────────────────────────
  # 3. 获奖荣誉 (Honors & Awards)
  # 【修复点】改用 Markdown 组件，100%不会报错
  # ────────────────────────────────────────────────────────────
  - block: markdown
    id:awards
    content:
      title: '🏆 Honors & Awards'
      subtitle: ''
      text: |-
        *   **2025.11**: Second Prize, National College Student Mathematics Competition (Anhui Division)
            *   第17届全国大学生数学竞赛安徽赛区二等奖
        *   **2024.09**: Second Prize, National High School Physics Olympiad (Anhui Division)
            *   第41届全国中学生物理竞赛安徽赛区二等奖
    design:
      columns: '1'

  # ────────────────────────────────────────────────────────────
  # 4. 学术兴趣 (Research Interests)
  # ────────────────────────────────────────────────────────────
  - block: markdown
    id:interests
    content:
      title: '🔬 Academic Interests'
      subtitle: ''
      text: |-
        I am currently a freshman exploring various fields in **Physics**. 
        
        *   **Physics**: I have not yet decided on a specific sub-field but I am exploring areas such as **Condensed Matter Physics** and **Quantum Information**. My current goal is to build a solid foundation in theoretical physics (Four Mechanics) to broaden my horizons.
        *   **Interdisciplinary**: I also have a keen interest in **Deep Learning** and **Artificial Intelligence**, looking for opportunities to combine AI with physical sciences.
        
        I am open to communication with professors and seniors to explore research opportunities.
    design:
      columns: '1'

  # ────────────────────────────────────────────────────────────
  # 5. 待启用板块 (Hidden / Future Use)
  # ────────────────────────────────────────────────────────────

  # [精选论文]
  # - block: collection
  #   id: papers
  #   content:
  #     title: Featured Publications
  #     filters:
  #       folders:
  #         - publications
  #       featured_only: true
  #   design:
  #     view: article-grid
  #     columns: 2

  # [最近发表]
  # - block: collection
  #   content:
  #     title: Recent Publications
  #     text: ''
  #     filters:
  #       folders:
  #         - publications
  #       exclude_featured: false
  #   design:
  #     view: citation

  # [讲座与活动]
  # - block: collection
  #   id: talks
  #   content:
  #     title: Recent & Upcoming Talks
  #     filters:
  #       folders:
  #         - events
  #   design:
  #     view: card

  # [新闻动态]
  # - block: collection
  #   id: news
  #   content:
  #     title: Recent News
  #     subtitle: ''
  #     text: ''
  #     page_type: blog
  #     count: 10
  #     filters:
  #       author: ''
  #       category: ''
  #       tag: ''
  #       exclude_featured: false
  #       exclude_future: false
  #       exclude_past: false
  #       publication_type: ''
  #     offset: 0
  #     order: desc
  #   design:
  #     view: card
  #     spacing:
  #       padding: [0, 0, 0, 0]
---