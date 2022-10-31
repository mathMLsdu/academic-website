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
  email: yfxusdu@163.com
  phone: 888 888 88 88
  address:
    street: 27
    city: Jinan
    region: Licheng
    postcode: '250110'
    country: China
    country_code: CN
  coordinates:
    latitude: '36.65'
    longitude: '117'
  directions: Zhixin building block B 1108
  office_hours:
    - 'Monday 08:00 to 23:00'
    - 'Wednesday 09:00 to 10:00'
  appointment_url: 'https://calendly.com'
  contact_links:
    - icon: twitter
      icon_pack: fab
      name: DM Me
      link: 'https://twitter.com/Twitter'

design:
  columns: '2'
---
