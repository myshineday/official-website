---
# Leave the homepage title empty to use the site title
title:
date: 2023-08-08
type: landing

sections:
  - block: about.biography
    id: home
    content:
      title: ShineDay - Habits Tracker
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin  
  - block: contact
    id: contact
    content:
      title: Contact
      subtitle: ''
      text: ''
      # Contact details - edit or remove options as needed
      email: myshineday@gmail.com
      office_hours:
        - '09:00 to 17:00'
      contact_links:
        - icon: weibo
          icon_pack: fab
          name: Follow Me
          link: 'https://weibo.com/hangsplace'
      # Automatically link email and phone or display them just as text?
      autolink: true
      # Choose an email form provider (netlify/formspree)
      # form:
      #   provider: netlify
      #   formspree:
      #     # If using Formspree, enter your Formspree form ID
      #     id: ''
      #   netlify:
      #     # Enable CAPTCHA challenge to reduce spam?
      #     captcha: true
      # Coordinates to display a map - set your map provider in `params.yaml`
      # coordinates:
      #   latitude: '37.4275'
      #   longitude: '-122.1697'
    design:
      # Choose how many columns the section has. Valid values: '1' or '2'.
      columns: '2'            
---
