---
# An instance of the Contact widget.
widget: contact

# This file represents a page section.
headless: true

# Order that this section appears on the page.
weight: 70

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
  email: stefan.oppl@donau-uni.ac.at
  phone: +43 2732 893-2500
  address:
    street: Dr.-Karl-Dorrek-Straße 30
    city: Krems
    postcode: '3500'
    country: Austria
    country_code: AT
  coordinates:
    latitude: '48.407885'
    longitude: '15.586026'
  directions: Enter Building Altbau, and take the stairs to 2nd Floor, Tract L, Room 2.208-1 
  office_hours: upon appointment
  contact_links:
    - icon: twitter
      icon_pack: fab
      name: DM Me
      link: 'https://twitter.com/stefanoppl'

design:
  columns: '2'
---
