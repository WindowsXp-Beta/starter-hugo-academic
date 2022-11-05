---
# An instance of the Experience widget.
# Documentation: https://wowchemy.com/docs/page-builder/
widget: experience

# This file represents a page section.
headless: true

# Order that this section appears on the page.
weight: 50

title: Intern Experience
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
  - title: Software Engineer intern
    company: Microsoft Dynamics 365
    company_url: 'https://dynamics.microsoft.com/en-us/'
    company_logo: Microsoft_logo
    location: Shanghai, China
    date_start: '2022-06-20'
    date_end: '2022-09-14'
    description: |2-
        Responsibilities include:
        * Participated in developing Dynamics365 Assistance, an AIBot deployed on Azure.
        * Fixed bugs and did some refactoring for QuickAccess.
        * Developed tools facilitating FTE’s daily development including an script maintaining RCAs on Azure devops, a test automation tool, etc.

  - title: Database System R&D Intern
    company: RisingWave Labs
    company_url: 'https://www.risingwave-labs.com/'
    company_logo: rwicon
    location: Shanghai, China
    date_start: '2022-02-23'
    date_end: '2022-06-19'
    description: |2-
      Participate in developing [RisingWave](https://github.com/risingwavelabs/risingwave), the next-generation cloud native streaming database.
      - Refined system's value encoding.
      - Implemented common table expressions for front end.
      - Implemented internal table catalog, including inference and storage.

design:
  columns: '2'
---
