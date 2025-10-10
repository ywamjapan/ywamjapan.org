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
      id: mleoznje
    netlify:
      # Enable CAPTCHA challenge to reduce spam?
      captcha: false

  # Contact details (edit or remove options as required)
  email: info@ywamsendai.org
  #phone: 0263-87-0034
  address:
  #  street: 2303-4 Misatomeisei
    city: Sendai
    region: Miyagi
    #postcode: '399-8201'
    country: Japan
    country_code: JP
  coordinates:
    latitude: '38.2728'
    longitude: '140.761462'
  #directions: Enter Building 1 and take the stairs to Office 200 on Floor 2
  #office_hours:
  #  - 'Monday 10:00 to 13:00'
  #  - 'Wednesday 09:00 to 10:00'
  #appointment_url: 'https://calendly.com'
  contact_links:
    - icon: x-twitter
      icon_pack: fab
      name: X
      link: 'https://www.x.com/ywamsendai'
    - icon: instagram
      icon_pack: fab
      name: Instagram
      link: 'https://www.instagram.com/ywamsendai'
    - icon: discord
      icon_pack: fab
      name: Discord
      link: 'https://discord.gg/djmCF4DBaV'
    - icon: globe
      icon_pack: fas
      name: Website
      link: 'https://www.ywamsendai.org'

design:
  columns: '2'
---
