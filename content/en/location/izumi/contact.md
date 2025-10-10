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
  email: info@ywamizumi.com
  #phone: 080-4388-3927
  address:
    street: 4-3-82 Fuseyacho
    city: Izumi city
    region: Osaka
    postcode: '594-0031'
    country: Japan
    country_code: JP
  coordinates:
    latitude: '34.47235'
    longitude: '135.46478'
  #directions: Enter Building 1 and take the stairs to Office 200 on Floor 2
  #office_hours:
  #  - 'Monday 10:00 to 13:00'
  #  - 'Wednesday 09:00 to 10:00'
  #appointment_url: 'https://calendly.com'
  contact_links:
    - icon: instagram
      icon_pack: fab
      name: Instagram
      link: 'https://www.instagram.com/ywam.izumi'
  #  - icon: globe
  #    icon_pack: fas
  #    name: Website
  #    link: 'https://ywamniseko.org'

design:
  columns: '2'
---
