---
# An instance of the Experience widget.
# Documentation: https://wowchemy.com/docs/page-builder/
widget: experience

# This file represents a page section.
headless: true

# Order that this section appears on the page.
weight: 50

title: Research Experience
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
  - title: Serving DNN Models with Multi-Instance GPUs
    company: Northeastern University, Systems Research Group
    company_url: 'https://srg.khoury.northeastern.edu/'
    company_logo: neu
    location: Boston, MA, US
    date_start: '2022-09-01'
    date_end: '2023-05-01'
    adviser: Tan Cheng
    description: |2-
        - Adviser: [Prof. Cheng Tan](https://www.khoury.northeastern.edu/people/cheng-tan/)
        - Built a benchmarking tool to measure different machine learning models' performance on Multi-Instance GPU.
        - Implemented a "exchange-and-compact" development transition algorithm on top of Kubernetes.
        - Optimized the transition time from 30' to 1'.
        - Built the testbed containing 4-instances on GCP and carried out a 24-hour end to end test.

  - title: Secure Personal Data Storage and Analysis System
    company: Institute of Parallel and Distributed Systems(IPADS)
    company_url: 'https://ipads.se.sjtu.edu.cn/'
    company_logo: sjtu
    location: Shanghai, China
    date_start: '2021-09-01'
    date_end: '2022-09-01'
    description: |2-
        - Adviser: Prof. [Yubin Xia](https://ipads.se.sjtu.edu.cn/pub/members/yubin_xia) and [Ph.D. Mingyu Li](https://maxul.github.io/)
        - Implemented a secure personal data analysis and storage system on Hikey960 using OPTEE and AOSP.
        - Designed and developed an app to generate SJTU students’ personal annual report.
        - Participated in Shanghai “Internet+” College Student Innovation and Entrepreneurship Contest as an SJTU representative.

design:
  columns: '2'
---
