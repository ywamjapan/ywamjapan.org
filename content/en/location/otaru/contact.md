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
    provider:
    formspree:
      id:
    netlify:
      # Enable CAPTCHA challenge to reduce spam?
      captcha: false

  # Contact details (edit or remove options as required)
  email: ywamotaru.info@gmail.com
  phone: 080-4722-4471
  address:
    #street: Niseko
    city: Otaru
    region: Hokkaido
    #postcode: '399-8201'
    country: Japan
    country_code: JP
  coordinates:
    latitude: '43.156463748559545'
    longitude: '141.02507286098734'
  #directions: Enter Building 1 and take the stairs to Office 200 on Floor 2
  #office_hours:
  #  - 'Monday 10:00 to 13:00'
  #  - 'Wednesday 09:00 to 10:00'
  #appointment_url: 'https://calendly.com'
  contact_links:
    - icon: instagram
      icon_pack: fab
      name: DM Me
      link: 'https://instagram.com/ywamotaru'
    - icon: globe
      icon_pack: fas
      name: Website
      link: 'https://ywamotaru.org'

design:
  columns: '2'
---
