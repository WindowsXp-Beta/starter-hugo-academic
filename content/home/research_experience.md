---
# An instance of the Experience widget.
# Documentation: https://wowchemy.com/docs/page-builder/
widget: experience

# This file represents a page section.
headless: true

# Order that this section appears on the page.
weight: 40

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
  - title: Research Assistant
    company: Northeastern University Systems Research Group
    company_url: 'https://srg.khoury.northeastern.edu/'
    company_logo: neu
    location: Boston, MA
    date_start: '2022-09-01'
    # date_end: '2023-09-01'
    description: |2-
        - Built a benchmarking tool for 16 machine learning models on PyTorch HUB to get their performance (throughput and tail-latency).
        - Implemented a "exchange-and-compact" development transition algorithm and integrated it with Kubernetes.
        - Optimized the transition time from 30' to 1'.
        - Passed a 24-hour end to end test on a 4-instances cluster on GCP.

  - title: PRP Project Leader
    company: Institute of Parallel and Distributed Systems(IPADS)
    company_url: 'https://ipads.se.sjtu.edu.cn/'
    company_logo: sjtu
    location: Shanghai, China
    date_start: '2021-09-01'
    date_end: '2022-09-01'
    description: |2-
        - Implemented a secure personal data analysis and storage system on Hikey960 using OPTEE and AOSP.
        - Designed and developed an app to generate SJTU students’ personal annual report.
        - Participated in Shanghai “Internet+” College Student Innovation and Entrepreneurship Contest as an SJTU representative.

design:
  columns: '2'
---
