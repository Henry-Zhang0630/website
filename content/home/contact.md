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
  email: zhanheg@connect.hku.hk
  address:
    street: Jockey Club Student Village III
    city: HongKong
    region: HK
  coordinates:
    latitude: '37.4275'
    longitude: '-122.1697'
  directions: Lap-Chee College
  office_hours:
    - 'Monday 10:00 to 13:00'
    - 'Wednesday 09:00 to 10:00'

design:
  columns: '2'
---
