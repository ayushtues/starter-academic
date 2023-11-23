---
# Leave the homepage title empty to use the site title
title: "Ayush Mangal"
date: 2022-10-24
type: landing

sections:
  - block: about.biography
    id: about
    content:
      title: Biography
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
  - block: experience
    content:
      title: Experience
      # Date format for experience
      #   Refer to https://wowchemy.com/docs/customization/#date-format
      date_format: Jan 2006
      # Experiences.
      #   Add/remove as many `experience` items below as you like.
      #   Required fields are `title`, `company`, and `date_start`.
      #   Leave `date_end` empty if it's your current employer.
      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
      items:
        - title: Data & Applied Scientist
          company: Microsoft
          company_url: 'https://bing.com/travel'
          company_logo: msft
          location: Hyderbad, India
          date_start: '2022-06-27'
          date_end: ''
          description: |2-
              Creating and maintaining various data-pipelines for visual content and  developing novel methods to maintain image quality at scale. 
        - title: Research Intern
          company: Rephrase.ai
          company_url: 'https://www.rephrase.ai/'
          company_logo: rephrase
          location: Bangalore, India
          date_start: '2021-12-01'
          date_end: '2022-01-01'
          description: A deep‐tech startup that creates personalized videos for marketing using DL
        - title: Research Intern
          company: RVL Lab, University Of Toronto
          company_url: 'https://rvl.cs.toronto.edu/'
          company_logo: rvl
          location: Prof. Florian Shkurti
          date_start: '2021-08-01'
          date_end: '2022-05-01'
          description: Worked on Model based Deep Heirarchial RL 
        - title: Research Intern
          company: Machinge Learning Department, Carneighe Mellon University
          company_url: 'https://www.cs.cmu.edu/~katef/'
          company_logo: mld
          location: Prof. Katerina Fragkiadaki
          date_start: '2020-06-01'
          date_end: '2021-02-01'
          description: Worked on Unsupervised 3D Multi-Object Tracking
        - title: Research Intern
          company: MIDAS Lab, IIITD
          company_url: 'https://midas.iiitd.ac.in/'
          company_logo: midas
          location: Prof. Rajiv Ratn Shah
          date_start: '2020-03-01'
          date_end: '2021-04-01'
          description: Worked on various multimodal NLP + Finance projects
        - title: Research Intern
          company: VAL, IISC Bangalore
          company_url: 'https://val.cds.iisc.ac.in/'
          company_logo: val
          location: Prof. Venkatesh Babu
          date_start: '2019-12-01'
          date_end: '2020-01-01'
          description: Worked on deep computational photography
    design:
      columns: '2'
  - block: collection
    id: featured
    content:
      title: Featured Publications
      filters:
        folders:
          - publication
        featured_only: true
    design:
      columns: '1'
      view: showcase
  - block: portfolio
    id: projects
    content:
      title: Projects
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
      buttons:
        - name: All
          tag: '*'
        - name: Diffusers
          tag: Diffusers
        - name: Paper Implementations
          tag: Paper Implementations
        - name: LLM
          tag: LLM
    design:
      # Choose how many columns the section has. Valid values: '1' or '2'.
      columns: '1'
      view: masonry
      # For Showcase view, flip alternate rows?
      flip_alt_rows: false
  - block: experience
    content:
      title: Extra-Curriculars
      # Date format for experience
      #   Refer to https://wowchemy.com/docs/customization/#date-format
      date_format: Jan 2006
      # Experiences.
      #   Add/remove as many `experience` items below as you like.
      #   Required fields are `title`, `company`, and `date_start`.
      #   Leave `date_end` empty if it's your current employer.
      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
      items:
        - title: Co-President
          company: Vision & Language Group, ACM IITR
          company_url: 'https://vlgiitr.github.io/'
          company_logo: vlg
          location: IIT Roorkee
          date_start: '2019-09-27'
          date_end: '2022-05-01'
          description: |2-
              Deep Learning Research Group
        - title: Youtuber
          company: RR With Deku
          company_url: 'https://www.youtube.com/channel/UCGEWHZv8Gn10Lk56PzCeFMA'
          company_logo: rr
          location: Youtube
          date_start: '2020-10-01'
          date_end: ''
          description: A Youtube Channel for discussing recent Deep Learning papers.
        - title: Founder
          company: BlocSoc IITR
          company_url: 'https://blocsoc.iitr.ac.in/'
          company_logo: blocsoc
          location: IIT Roorkee
          date_start: '2021-10-01'
          date_end: '2022-05-01'
          description: Blockchain & Web3 Group
        - title: Chair
          company: ACM IITR
          company_url: 'https://iitr.acm.org/#/'
          company_logo: acm
          location: IIT Roorkee
          date_start: '2021-03-01'
          date_end: '2022-05-01'
          description: Core CS Research Group
        - title: Executive Member
          company: Quantum Computing Group, ACM IITR
          company_url: 'https://qcg.iitr.ac.in/'
          company_logo: qcg
          location: IIT Roorkee
          date_start: '2021-03-01'
          date_end: '2022-05-01'
          description: Quantum Computing Research Group
    design:
      columns: '1'
  - block: portfolio
    id: video
    content:
      title: Recent Videos
      filters:
        folders:
          - videos
      # Default filter index (e.g. 0 corresponds to the first `filter_button` instance below).
      default_button_index: 0
      # Filter toolbar (optional).
      # Add or remove as many filters (`filter_button` instances) as you like.
      # To show all items, set `tag` to "*".
      # To filter by a specific tag, set `tag` to an existing tag name.
      # To remove the toolbar, delete the entire `filter_button` block.
      buttons:
        - name: Diffusion
          tag: diffusion
        - name: RL
          tag: rl
        - name: LLM
          tag: LLM
    design:
      # Choose how many columns the section has. Valid values: '1' or '2'.
      columns: '1'
      view: masonry
      # For Showcase view, flip alternate rows?
      flip_alt_rows: true
  - block: contact
    id: contact
    content:
      title: Contact
      subtitle:
      text: |-

      # Contact (add or remove contact options as necessary)
      email: ayushtues@gmail.com
      contact_links:
        - icon: twitter
          icon_pack: fab
          name: DM Me
          link: 'https://twitter.com/ayush_tues'
      # Automatically link email and phone or display as text?
      autolink: true
      # Email form provider
      form:
        provider: netlify
        formspree:
          id:
        netlify:
          # Enable CAPTCHA challenge to reduce spam?
          captcha: false
    design:
      columns: '2'
---
