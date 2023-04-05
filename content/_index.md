---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:
  - block: about.avatar
    id: about
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
      # Override your bio text from `authors/admin/_index.md`?
      text:
  # - block: experience
  #   id: experience
  #   content:
  #     title: Experience
  #     # Date format for experience
  #     #   Refer to https://wowchemy.com/docs/customization/#date-format
  #     date_format: Jan 2006
  #     # Experiences.
  #     #   Add/remove as many `experience` items below as you like.
  #     #   Required fields are `title`, `company`, and `date_start`.
  #     #   Leave `date_end` empty if it's your current employer.
  #     #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
  #     items:
  #       - title: Student
  #         company: South Brunswick High School
  #         company_url: ''
  #         company_logo: ''
  #         location: Monmouth Junction, NJ
  #         date_start: '2020-09-01'
  #         date_end: ''
  #         description: |2-
  #             Courses:
  # 
  #             * AP Chemistry
  #             * AP Biology
  #             * AP Calculus
  #             * AP Computer Science A
  #             * Mobile Application Development
  #   design:
  #     columns: '2'
  # - block: accomplishments
  #  id: accomplishments
  #  content:
      # Note: `&shy;` is used to add a 'soft' hyphen in a long heading.
     # title: 'Accomplishments'
    #  subtitle:
      # Date format: https://wowchemy.com/docs/customization/#date-format
      # date_format: Jan 2006
      # Accomplishments.
      #   Add/remove as many `item` blocks below as you like.
      #   `title`, `organization`, and `date_start` are the required parameters.
      #   Leave other parameters empty if not required.
      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
    #  items:
     #   - certificate_url: 
     #     date_end: ''
     #     date_start: '2020-09-01'
      #    description: ''
    #      organization: 
    #      organization_url: 
    #      title: 
    #      url: ''
    # design:
    #  columns: '2'
  - block: collection
    id: publications
    content:
      title: Projects
      filters:
        folders:
          - publication
        exclude_featured: true
    design:
      columns: '2'
  - block: contact
    id: contact
    content:
      title: Contact Me
      subtitle:
      text: |-
        If you have any questions, fill out the form below and I will get back to you as soon as possible.
      # Contact (add or remove contact options as necessary)
      email: rishantilve@gmail.com
      # phone: 888 888 88 88
      # appointment_url: 'https://calendly.com'
      address:
        # street: 450 Serra Mall
        city: Monmouth Junction
        region: NJ
        # postcode: ''
        country: United States
        country_code: US
      # directions: Enter Building 1 and take the stairs to Office 200 on Floor 2
      # contact_links:
      #  - icon: twitter
      #    icon_pack: fab
      #    name: DM Me
      #    link: 'https://twitter.com/Twitter'
      #  - icon: skype
      #    icon_pack: fab
      #    name: Skype Me
      #    link: 'skype:echo123?call'
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
