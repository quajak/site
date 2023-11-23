---
# Leave the homepage title empty to use the site title
title:
date: 2023-08-16
type: landing

sections:
  - block: about.biography
    id: about
    content:
      title: Jasper Gerigk
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
  # - block: features
  #   content:
  #     title: Skills
  #     items:
  #       - name: R
  #         description: 90%
  #         icon: r-project
  #         icon_pack: fab
  #       - name: Statistics
  #         description: 100%
  #         icon: chart-line
  #         icon_pack: fas
  #       - name: Photography
  #         description: 10%
  #         icon: camera-retro
  #         icon_pack: fas
  - block: collection
    content:
      title: PUBLICATIONS 
      # text: |-
      filters:
        folders:
          - publication
        exclude_featured: false
    design:
      columns: '1'
      view: citation
  - block: accomplishments
    content:
      # Note: `&shy;` is used to add a 'soft' hyphen in a long heading.
      title: EXPERIENCE
      subtitle:
      # Date format: https://wowchemy.com/docs/customization/#date-format
      date_format: Jan 2006
      # Accomplishments.
      #   Add/remove as many `item` blocks below as you like.
      #   `title`, `organization`, and `date_start` are the required parameters.
      #   Leave other parameters empty if not required.
      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
      items:
        - certificate_url: ''
          date_end: '2023-08-31'
          date_start: '2023-05-01'
          description: |-
            Member of the TISL research group led by Professor Gilitschenski <br>
            Worked on combining pre-trained computer vision models with reinforcement learning <br>
            Methods applied: Pytorch, JAX, Rainbow, SAM, FastSAM
          organization: Data Science Institute, University of Toronto, Toronto, Canada
          organization_url: https://datasciences.utoronto.ca/suds/
          title: DSI SUDS Scholar
          url: ''
          organisation_url: data_science_institute
          svg_icon: 'https://datasciences.utoronto.ca/wp-content/uploads/2021/05/DSI-Reverse-Signature-Lock-Up_Screen-768x124.png' 
        - certificate_url: ''
          date_end: '2022-08-01'
          date_start: '2022-05-01'
          description: |-
            Member of the Fleet Learning for Automated Driving team <br>
            For the first time, used large-scale customer fleet data to analyze lateral vehicle movement to improve comfort of lane following assistant <br>
            Methods applied: Spark, Azure Databricks, Frequentist and Bayesian statistics in Python 
          organization: Mercedes Benz AG, Böblingen, Germany
          organization_url: https://www.mercedes-benz.de/
          title: Data Analytics Internship 
          url: ''
          organisation_url: mercedes_benz_ag
        - certificate_url: ''
          date_end: '2022-04-01'
          date_start: '2021-10-01'
          description: |-
            Member of BMWK-funded research project <a href="https://projekt-lukas.de/"> "Lokales Umfeldmodell für das Kooperative, Automatisierte Fahren in komplexen Verkehrssituationen" </a> <br>
            Development of multi-agent reinforcement learning algorithms for centralized planning of connected self-driving vehicles using graph neural networks <br>
            Methods applied: DQN, TD3, RCGN, GAT implemented in Python using PyTorch
          organization: Robert Bosch GmbH, Renningen, Germany
          organization_url: https://www.bosch.com/company/
          title: 'Corporate Research Internship '
          url: 'https://www.projekt-lukas.de/'
          organisation_url: robert_bosch_gmbh
        - certificate_url: ''
          date_start: '2020-06-01'
          date_end: '2020-09-01'
          description: |-
            Designed and built functional software demonstration based on Server-Side Blazor (C#) <br>
            Contributed to backend by integrating machine learning methods using Python
          organization: Excubo AG, Zug, Switzerland
          organisation_url: excubo
          title: 'Software Development Internship'
          url: http://excubo-ag.com/
        - certificate_url: ''
          date_start: '2018-05-14'
          # date_end: '2018-05-01'
          description: |-
            Created instructional material for AI undergraduate course at TU Kaiserslautern on Reinforcement Learning including Deep-Q learning for Brick Breaker using PyTorch
          organization: German Research Center for Artificial Intelligence (DFKI), Kaiserslautern, Germany
          organisation_url: dfki
          title: 'Student Internship'
          url: https://www.dfki.de/en/web/
        - certificate_url: ''
          date_start: '2016-06-14'
          # date_end: '2016-06-01'
          description: |-
            Implemented linear least squares for multiclass classification of geographic coordinates
          organization: Fraunhofer Institute for Intelligent Analysis and Information Systems, St. Augustin, Germany
          organisation_url: fiais
          title: 'Student Internship'
          url: https://www.iais.fraunhofer.de/
    design:
      columns: '2'
  - block: education 
    content:
      title: EDUCATION
      # Date format for experience
      #   Refer to https://wowchemy.com/docs/customization/#date-format
      date_format: Jan 2006
      # Experiences.
      #   Add/remove as many `experience` items below as you like.
      #   Required fields are `title`, `company`, and `date_start`.
      #   Leave `date_end` empty if it's your current employer.
      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
      items:
        - title: Bachelor of Science
          company: University of Toronto
          company_url: ''
          company_logo: uoft
          location: Toronto, Canada
          date_start: '2019-09-01'
          date_end: ''
          description: |3-
              GPA: 3.96/4.0

              Programs:
              
              * Computer Science Specialist 
              * Focus In Artificial Intelligence
              * Mathematics Major
            

              <p style="padding-top: 16px;">
              Advanced Courses:
              </p>

              * CSC311: Introduction to Machine Learning
              * CSC324: Principles of Programming Languages
              * CSC412: Probabilistic Learning and Reasoning
              * CSC413: Neural Networks and Deep Learning
              * CSC420: Introduction to Image Understanding
              * CSC494: Computer Science Project: Developed and published agent for Dominion under supervision of Professor Engels
             

              <p style="padding-top: 16px;">
              Awards:
              </p>

              * 2020, 2023 - Dean's List Scholar
              * 2019 - 2020 - Millard Scholarship ($1208)
              * 2022 - 2023 - Dr. James A. & Connie P. Dickson Scholarship In Science & Mathematics ($500): Recognizes best University College students in science and mathematics
              * 2022 - 2023 - University of Toronto Scholar ($1500): Recognizes the most outstanding students across all three campuses of the University of Toronto 
        - title: Bachelor of Science - Exchange
          company: Technical University of Darmstadt
          company_url: ''
          company_logo: darmstadt
          location: Darmstadt, Germany
          date_start: '2020-11-01'
          date_end: '2021-05-01'
          description: |-            
            Courses covering: 
            * Statistical Machine Learning
            * Natural Language Processing using Deep Learning
        - title: Bachelor of Science - Exchange
          company: Johannes Gutenberg University Mainz
          company_url: ''
          company_logo: mainz
          location: Mainz, Germany
          date_start: '2020-11-01'
          date_end: '2021-08-31'
          description: |-
            Courses covering: 
            * Linear Algebra 
            * Probability and Statistics
            * Numerical Methods
    design:
      columns: '1'

  # - block: collection
  #   id: posts
  #   content:
  #     title: Recent Posts
  #     subtitle: ''
  #     text: ''
  #     # Choose how many pages you would like to display (0 = all pages)
  #     count: 5
  #     # Filter on criteria
  #     filters:
  #       folders:
  #         - post
  #       author: ""
  #       category: ""
  #       tag: ""
  #       exclude_featured: false
  #       exclude_future: false
  #       exclude_past: false
  #       publication_type: ""
  #     # Choose how many pages you would like to offset by
  #     offset: 0
  #     # Page order: descending (desc) or ascending (asc) date.
  #     order: desc
  #   design:
  #     # Choose a layout view
  #     view: compact
  #     columns: '2'
  - block: portfolio
    id: projects
    content:
      title: PROJECTS
      filters:
        folders:
          - project
      # Default filter index (e.g. 0 corresponds to the first `filter_button` instance below).
      default_button_index: 0
      # Filter toolbar (optional).
      # Add or remove as many filters (`filter_button` instances) as you like.
      # To show all items, set `tag` to "*".
      # To filter by a specific tag, set `tag` to an existing tag name.
      # To remove the toolbar, delete the entire `filter_button` block.
      buttons: []
        # - name: All
        #   tag: '*'
        # - name: Deep Learning
        #   tag: Deep Learning
        # - name: Other
        #   tag: Demo
    design:
      # Choose how many columns the section has. Valid values: '1' or '2'.
      columns: '2'
      view: showcase
      # For Showcase view, flip alternate rows?
      flip_alt_rows: false
  # - block: markdown
  #   content:
  #     title: Gallery
  #     subtitle: ''
  #     text: |-
  #       {{< gallery album="demo" >}}
  #   design:
  #     columns: '1'
  # - block: collection
  #   id: featured
  #   content:
  #     title: Featured Publications
  #     filters:
  #       folders:
  #         - publication
  #       featured_only: true
  #   design:
  #     columns: '2'
  #     view: card

  # - block: collection
  #   id: talks
  #   content:
  #     title: Recent & Upcoming Talks
  #     filters:
  #       folders:
  #         - event
  #   design:
  #     columns: '2'
  #     view: compact
  # - block: tag_cloud
  #   content:
  #     title: Popular Topics
  #   design:
  #     columns: '2'
  - block: contact
    id: contact
    content:
      title: CONTACT
      subtitle:
      text: '' 
      # Contact (add or remove contact options as necessary)
      email: jasper.gerigk@mail.utoronto.ca
      # phone: 888 888 88 88
      # appointment_url: 'https://calendly.com'
      # address:
      #   street: 450 Serra Mall
      #   city: Stanford
      #   region: CA
      #   postcode: '94305'
      #   country: United States
      #   country_code: US
      # directions: Enter Building 1 and take the stairs to Office 200 on Floor 2
      # office_hours:
      #   - 'Monday 10:00 to 13:00'
      #   - 'Wednesday 09:00 to 10:00'
      # contact_links:
        # - icon: twitter
        #   icon_pack: fab
        #   name: DM Me
        #   link: 'https://twitter.com/Twitter'
        # - icon: skype
        #   icon_pack: fab
        #   name: Skype Me
        #   link: 'skype:echo123?call'
        # - icon: video
        #   icon_pack: fas
        #   name: Zoom Me
        #   link: 'https://zoom.com'
      # Automatically link email and phone or display as text?
      autolink: true
      # Email form provider
      # form:
      #   provider: netlify
      #   formspree:
      #     id:
      #   netlify:
      #     # Enable CAPTCHA challenge to reduce spam?
      #     captcha: false
    design:
      columns: '2'
---
