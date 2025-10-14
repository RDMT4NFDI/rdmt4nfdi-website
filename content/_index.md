---
# Leave the homepage title empty to use the site title
title: RDMT4NFDI - Research Data Management Training for NFDI
date: 2025-09-02
type: landing

sections:
  - block: hero
    content:
      title: RDMT4NFDI
      image:
        filename: _RDMTraining4NFDI.png
      text: |
        RDMTraining4NFDI delivers hands-on training in research data management (RDM) for all NFDI consortia. Our courses cover data, software, and machine-learning models and target consortia staff - such as data stewards and trainers - as well as researchers within each community. We develop a modular collection of core RDM training materials and proven training formats and methods. By using these resources, consortia can quickly create community-specific adaptations and expand their capacity efficiently. We also provide consultancy on training skills and methodologies and explore certification options to set quality standards and recognize participants' achievements.

        {{% cta cta_link="./about/" cta_text="Read more →" %}}

      # TODO here also other services could be linked which you provide, e.g. a hub or the documentation
  
#  - block: collection
#    content:
#      title: Latest News
#      subtitle:
#      text:
#      count: 3
#      filters:
#        author: ''
#        category: ''
#        exclude_featured: false
#        publication_type: ''
#        tag: ''
#        folders:
#          - news
#      offset: 0
#      order: desc
#    design:
#      view: card
#      columns: '1'

  - block: collection
    content:
      title: Latest Publications
      text: ""
      count: 5
      filters:
        folders:
          - publication
        #publication_type: 'article'
    design:
      view: list
      columns: '1'

  - block: markdown
    content:
      title:
      subtitle:
      text: |
        {{% cta cta_link="./people/" cta_text="Meet the team →" %}} {{% cta cta_link="./contact/" cta_text="Contact us →" %}}
    design:
      columns: '1'
---
