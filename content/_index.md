---
# Leave the homepage title empty to use the site title
title: RDMT4NFDI - Research Data Management Training for NFDI
date: 2025-09-02
type: landing

sections:
  - block: hero
    content:
      title: RDMTraining4NFDI
      image:
        filename: _RDMTraining4NFDI.png
      text: |
        RDMTraining4NFDI is a Base4NFDI basic service currently in its integration phase, focused on developing training and education in research data management and funded by the German Research Foundation (DFG) via Base4NFDI.

        During this phase, we will focus on advancing the harmonization of RDM training materials and the certification of RDM training together with the community.

        We provide RDM trainings targeting consortia staff such as Data Stewards and trainers.

        In addition, we offer consultancy on training skills and methodologies, helping consortia enhance the quality and impact of their RDM training.

        <p>
          <a class="btn btn-primary" data-toggle="collapse" href="#moreinfo" role="button" aria-expanded="false" aria-controls="moreinfo">
            Read more
          </a>
        </p>

        <div class="collapse" id="moreinfo">
          <p><strong>Harmonization of NFDI RDM materials:</strong> Together with our use cases, credentialing experts, and further initiatives, we will combine community concepts (Train-the-Trainer concept for RDM, the RDM learning objectives matrix, the EduBricks concept), insights and good practices from the community. The goal is to provide templates for a range of training formats, including workshops, courses, and self-learning units. These templates build on ongoing efforts of various initiatives. The templates are intended to support the creation of high-quality, reusable, and FAIR-aligned training materials for RDM education across the NFDI.</p>

          <p><strong>Certification Options:</strong> Certification is a key component for the standardization of RDM training within the NFDI and beyond. We are exploring options for how a certification process in the NFDI could be designed and implemented. In this phase, we aim to gain practical experience with micro-credentialing to identify and reduce potential barriers to the acceptance and implementation of a credentialing process.</p>

          <p><strong>Training Execution:</strong> Data Stewards will have the opportunity to participate in RDM training courses covering a range of topics. Our RDM training courses cover data, software, and machine learning models and didactics. We offer quarterly online RDM training sessions as well as on-site training sessions twice a year. We also offer generic foundational RDM training for researchers within the consortia.</p>

          <p><strong>Training Consultancy:</strong> We offer training consultancy, either in the form of tailored training sessions or advice on the didactic design and delivery of RDM training.</p>

          <p><strong>RDM Network:</strong> We are in contact with several stakeholders within the NFDI, such as RDM trainers, and beyond, including Data Competence Centers (DKZ), regional initiatives, and RDM projects like the UAG Schulungen/Fortbildungen der DINI/nestor-AG Forschungsdaten. This network enables us to connect you with relevant projects and contacts whenever you need a point of reference.</p>
        </div>



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
