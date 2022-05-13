---
# An instance of the Contact widget.
widget: contact

# This file represents a page section.
headless: true

# Order that this section appears on the page.
weight: 130

title: Contact
subtitle:

content:
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

  # Contact details (edit or remove options as required)
  email: chs37@psu.edu
  phone: 734.945.0616
  address:
    street: 1001 Oswald Tower, The Pennsylvania State University
    city: University Park
    region: PA
    postcode: '16802'
    country: United States
    country_code: US
  coordinates:
    latitude: 
    longitude: 
  directions: 
  office_hours:
  appointment_url: ''
  contact_links:
    - icon: twitter
      icon_pack: fab
      name: DM Me
      link: 'https://twitter.com/Chris_H_Seto'
    #- icon: video
    #  icon_pack: fas
    #  name: Zoom Me
    #  link: 'https://zoom.com'

design:
  columns: '2'
---
