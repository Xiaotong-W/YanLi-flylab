---
title: Contact
date: 2024-12-19

type: landing

sections:
  - block: contact
    content:
      title: Contact
      text: You're welcome to reach out to members of the Li Lab for the latest updates on research, collaboration opportunities, internships, or any questions you may have!
      email: liyan(AT)ibp.ac.cn
      phone: 64888533
      address:
        institute: Institute of Biophysics 
        street: Datun Road, Chaoyang District
        city: Beijing
        postcode: '100101'
        country: China
      directions: Enter Building 5 and take the stairs on the right to Office 2209 on Floor 2
      #contact_links:
      #  - icon: comments
      #    icon_pack: fas
      #    name: Discuss on Forum
      #    link: 'https://discourse.gohugo.io'
    
      # Automatically link email and phone or display as text?
      autolink: true
    
      # Email form provider
      form:
        provider: netlify
        formspree:
          id:
        netlify:
          # Enable CAPTCHA challenge to reduce spam?
          captcha: true
    design:
      columns: '1'

  - block: markdown
    content:
      title:
      subtitle: ''
      text:
    design:
      columns: '1'
      background:
        image: 
          filename: contact.jpg
          filters:
            brightness: 1
          parallax: false
          position: center
          size: cover
          text_color_light: true
      spacing:
        padding: ['20px', '0', '20px', '0']
      css_class: fullscreen
---
