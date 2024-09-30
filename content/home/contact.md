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
  email: chayan.chatterjee@vanderbilt.edu
  phone: +16153978537
  address:
    street: 2/24, Cook Street
    city: Perth
    region: Western Australia
    postcode: 6009
    country: Australia
    country_code: AUS
  coordinates:
    latitude: '-31.983247'
    longitude: '115.816675'
  contact_links:
    - icon: twitter
      icon_pack: fab
      name: DM Me
      link: 'https://twitter.com/ChayanChirps'

design:
  columns: '2'
---
