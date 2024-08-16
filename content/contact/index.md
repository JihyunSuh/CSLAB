---
title: Contact
date: 2022-10-24

type: landing

sections:
  - block: contact
    content:
      title: Contact
      text: |-
       If you have any questions about the research in the lab, please feel free to contact us. 
      email: jihyunsuh@postech.ac.kr
      phone: 888 888 88 88
      address:
        street: 77 Cheongam-ro, Nam-gu,
        city: Pohang-si
        region:  Gyeongsangbuk-do
        postcode: '37673'
        country: South Korea
        country_code: KOR
      coordinates:
        latitude: '36.01433836509526'
        longitude: '129.32323357738204'
      directions: Hogil Kim memorial hall Building, #404
      office_hours:
        - 'Monday 10:00 to 13:00'
        - 'Wednesday 09:00 to 10:00'
      appointment_url: 'https://calendly.com'
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
          captcha: false
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
