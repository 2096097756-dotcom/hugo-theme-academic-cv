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
      title: 'Professional Summary'
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
    id: education #
    content:
      title: '🎓 Education & Skills/教育背景与技能'
      subtitle: ''
      text: |-
        ### **Education/教育背景**
        
        *   **2025.09 - Present**: Undergraduate Student, **School of the Gifted Young (SGY)**, University of Science and Technology of China (**USTC**).
            *   **2025.09 - 至今**：中国科学技术大学(USTC)少年班学院(SGY)本科生
        *   **GPA**: 4.15 / 4.30 (Avg: 93.21)
        *   **Major**: Physics (Intended)
            *   **专业**：物理学（预期主修）
        *   **2023.09 - 2025.06**: High School Student, Hefei No.1 High School.
            *   **2023.09 - 2025.06**：合肥一中高中学生

        ### **Skills/技能**
        
        *   **Languages**: Chinese (Native), English (Learning)
            *   **语言**：中文（母语）、英语（学习中）
        *   **Programming**: C/C++ (Basic)
            *   **编程**：C/C++（基础）
        
        
    design:
      columns: '2'

  # ────────────────────────────────────────────────────────────
  # 3. 获奖荣誉 (Honors & Awards)
  # 【修复点】改用 Markdown 组件，100%不会报错
  # ────────────────────────────────────────────────────────────
  - block: markdown
    id: awards  #
    content:
      title: '🏆 Honors & Awards/获奖荣誉'
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
    id: interests  #
    content:
      title: '🔬 Academic Interests/学术兴趣'
      subtitle: ''
      text: |-
        I am currently a freshman exploring various fields in **Physics**.
        *   我是一名大一学生，正在探索物理学的各个领域。
        
        *   **Physics**: I have not yet decided on a specific sub-field but I am exploring areas such as **Condensed Matter Physics** and **Quantum Information**. My current goal is to build a solid foundation in theoretical physics (Four Mechanics) to broaden my horizons.
            *   **物理学**：我尚未确定具体的专业方向，但正在探索**凝聚态物理**和**量子信息**等领域。我目前的目标是为理论物理学(四大力学)打下坚实基础，以拓宽视野。
        *   **Interdisciplinary**: I also have a keen interest in **Deep Learning** and **Artificial Intelligence**, looking for opportunities to combine AI with physical sciences.
            *   **跨学科**：我还对**深度学习**和**人工智能**有浓厚的兴趣，寻求将AI与物理学结合的机会。
        
        I am open to communication with professors and seniors to explore research opportunities.
        *   我欢迎与教授和研究人员进行沟通，探索研究机会。
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