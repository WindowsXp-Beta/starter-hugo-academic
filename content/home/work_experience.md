---
# An instance of the Experience widget.
# Documentation: https://wowchemy.com/docs/page-builder/
widget: experience

# This file represents a page section.
headless: true

# Order that this section appears on the page.
weight: 40

title: Work Experience
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
  - title: Machine Learning System R&D Intern
    company: TikTok, Applied Machine Learning Team
    company_url: 'https://www.tiktok.com/en/'
    company_logo: tiktok_logo
    location: Beijing, China
    date_start: '2023-05-05'
    date_end: '2023-08-04'
    description: |2-
        * Integrated DeepSpeed to Bpex’s benchmarking tool to use distributed training and ZeRO to support larger models.
        * Wrote high-performance CUDA kernels for GEMM that utilize OP fusion, memory hierarchy and tensor cores.
        * Profiled performances of various attention implementations, analyzed in depth the differences between xFormers’s cutlass implementation and flash-attention(v1, v2), and delivered a comprehensive report in an internal presentation.

  - title: Software Engineer intern
    company: Microsoft, Cloud+AI Group
    company_url: 'https://dynamics.microsoft.com/en-us/'
    company_logo: Microsoft_logo
    location: Shanghai, China
    date_start: '2022-06-20'
    date_end: '2022-09-14'
    description: |2-
        * Developed and maintained a Teams Bot utilizing Microsoft Bot Framework and .NET core, which enables users to effortlessly query databases and request internal APIs using natural language.
        * Implemented QuickAccess, an admin web application to easily manipulate and search tax records using ASP.NET core MVC and Azure Cosmos DB.
        * Built tools utilizing Azure DevOps SDK to automate routine jobs including a daemon synchronizing data between task items and pull requests and a crawler maintaining data source for the Teams Bot, saving 10 working hours/month.

  - title: Database System R&D Intern
    company: RisingWave Labs
    company_url: 'https://www.risingwave.com/'
    company_logo: rwicon
    location: Shanghai, China
    date_start: '2022-02-23'
    date_end: '2022-06-19'
    description: |2-
      Participated in developing [RisingWave](https://github.com/risingwavelabs/risingwave), the next-generation cloud native streaming database.
      - Refined system's value encoding.
      - Implemented common table expressions for front end.
      - Implemented internal table catalog, including inference and storage.

design:
  columns: '2'
---
