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
  email: ywamkago@me.com
  phone: 0995-23-0766
  address:
    street: 大口里2698
    city: 伊佐市
    region: 鹿児島県
    postcode: '〒895-2511'
    country: 日本
    country_code: JP
  coordinates:
    latitude: '32.063857'
    longitude: '130.615639'
  #directions: Enter Building 1 and take the stairs to Office 200 on Floor 2
  #office_hours:
  #  - 'Monday 10:00 to 13:00'
  #  - 'Wednesday 09:00 to 10:00'
  #appointment_url: 'https://calendly.com'
  contact_links:
  #  - icon: twitter
  #    icon_pack: fab
  #    name: DM Me
  #    link: 'https://twitter.com/Twitter'
    - icon: globe
      icon_pack: fas
      name: Website
      link: 'http://hopekago.luna.weblife.me/index.html'

design:
  columns: '2'
---
