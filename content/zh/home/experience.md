---
# An instance of the Experience widget.
# Documentation: https://wowchemy.com/docs/page-builder/
widget: experience

# This file represents a page section.
headless: true

# Order that this section appears on the page.
weight: 40

title: 经验
subtitle:

# Date format for experience
#   Refer to https://wowchemy.com/docs/customization/#date-format
date_format: Jan 2006

# Experiences.
#   Add/remove as many `experience` items below as you like.
#   Required fields are `title`, `company`, and `date_start`.
#   Leave `date_end` empty if it's your current employer.
#   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
experience:
  - title: 访问学者
    company: 张斌课题组 @ 麻省理工学院
    company_url: http://zhanggroup.mit.edu/
    location: 远程工作（北京）
    date_start: '2020-06-21'
    date_end: '2020-10-13'
    description: |2-
        - 结合了归一化流方法与噪声对比学习方法，构建了从全原子模拟数据中学习粗粒化力场的方法
        - 取得了系统有效的学习模式，其训练难度与拟合的准确性优于较传统的受力拟合方法
  - title: 访问学者
    company: Teresa Head-Gordon 课题组 @ 伯克利加州大学
    company_url: https://thglab.berkeley.edu/
    location: 美国，加利福尼亚州
    date_start: '2019-12-16'
    date_end: '2020-03-07'
    description: |2-
        - 开发了一种利用扩展 Lagrangian 以及 Langevin 控温的方法求解含有多体电荷相互作用的系统
        - 消除了迭代求解电荷的过程，从而去除了 ReaxFF 等先进力场中主要的计算瓶颈，同时分子模拟得到的体系性质不受影响
        - 关于这一主题发表的论文参见[下方](#publications).
  - title: 交换学生研究员
    company: Daniel Neuhauser 课题组 @ 洛杉矶加州大学
    company_url: http://www.chem.ucla.edu/dept/Faculty/dxn/pages/home.html
    location: 美国加州
    date_start: '2019-09-23'
    date_end: '2019-12-15'
    description: |2-
        - 在含时 Bethe-Salpeter 方程的框架下引入了屏蔽势能项修正
        - 改善了体系光学性质计算的准确性
  - title: 本科生研究员
    company: 刘剑课题组 @ 北京大学
    company_url: http://jianliugroup.pku.edu.cn/
    location: 中国北京
    date_start: '2018-07-01'
    date_end: '2020-07-01'
    description: |2-
        - 利用辛几何与离散时间 Lyapunov 方程分析了路径积分分子动力学中的运动方程求解
        - 设计了可在较大时间步长下获得准确统计量的采样方案
---
