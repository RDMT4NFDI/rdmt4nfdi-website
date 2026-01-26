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
        RDMTraining4NFDI is a Base4NFDI basic service currently in its initialisation phase, focused on developing training and education in research data management and funded by the German Research Foundation (DFG) via Base4NFDI.
        
        RDMTraining4NFDI provides hands on research data management (RDM) training for all NFDI consortia. From the outset, we explore certification options to support standardization within the NFDI.

        Our RDM training courses cover data, software, and machine learning models and didactics, targeting consortia staff such as data stewards and trainers.

        We make RDM training materials, proven formats, and methods easily findable, reusable, and adaptable across consortia. This enables communities to efficiently tailor courses to their needs and scale their training capacity.

        In addition, we offer consultancy on training skills and methodologies, helping consortia enhance the quality and impact of their RDM training.

        <p>
          <a class="btn btn-primary" data-toggle="collapse" href="#moreinfo" role="button" aria-expanded="false" aria-controls="moreinfo">
            Read more
          </a>
        </p>

        <div class="collapse" id="moreinfo">
          <p><strong>Certification Options:</strong> Certification is a key component for the standardization of RDM training within the NFDI and beyond. We are exploring options for how a certification process in the NFDI could be designed and implemented.</p>

          <p><strong>Training Execution:</strong> We offer tailored RDM training courses based on community needs. From October to December 2025, our courses will focus on the most relevant topics, while gathering feedback on content quality, format, and participant satisfaction.</p>

          <p>In response to high demand, we also provide additional sessions on didactics and motivation. Stay updated by checking our announcements or contacting us to receive the latest information on upcoming trainings.</p>

          <p><strong>RDM Training Materials:</strong> Which training materials are suitable for which target groups? Which materials are qualified for reuse? We are exploring solutions to make training materials easier to find and reuse across consortia.</p>

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
