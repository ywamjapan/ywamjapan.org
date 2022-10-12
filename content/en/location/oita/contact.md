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
  email: info@ywamtokyo.org
  #phone: 0263-87-0034
  address:
  #  street: 2303-4 Misatomeisei
    city: Oita city
    region: Oita prefecture
    #postcode: '399-8201'
    country: Japan
    country_code: JP
  coordinates:
    latitude: '33.242238'
    longitude: '131.608024'
  #directions: Enter Building 1 and take the stairs to Office 200 on Floor 2
  #office_hours:
  #  - 'Monday 10:00 to 13:00'
  #  - 'Wednesday 09:00 to 10:00'
  #appointment_url: 'https://calendly.com'
  #contact_links:
  #  - icon: twitter
  #    icon_pack: fab
  #    name: DM Me
  #    link: 'https://twitter.com/Twitter'
   - icon: globe
      icon_pack: fas
      name: Website
      link: 'https://www.ywamoita.org/'

design:
  columns: '2'
---
