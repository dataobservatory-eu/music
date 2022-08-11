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
  email: ""
  phone: ""
  address:
    street: 
    city: The Hague
    region: Zuid-Holland
    postcode: ''
    country: Netherlands
    country_code: NL
  coordinates:
    latitude: '52.07'
    longitude: '4.313'
  directions: ""
  office_hours:
    - ''
  appointment_url: '/#contact'
  contact_links:
    - icon: twitter
      icon_pack: fab
      name: DM Me
      link: 'https://twitter.com/DigitalMusicObs'
    - icon: linkedin
      icon_pack: fab
      link: https://www.linkedin.com/company/79286750/

design:
  columns: '2'
---
