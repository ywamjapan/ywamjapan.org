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
  email: info@ywamtakatsuki.org
  phone: 07-2669-0555
  address:
    street: 2-15-3 Kanmaki-cho
    city: Takatsuki
    region: Osaka
    postcode: '569-0003'
    country: Japan
    country_code: JP
  coordinates:
    latitude: '34.864127'
    longitude: '135.662477'
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
      link: 'https://www.ywamtakatsuki.org'

design:
  columns: '2'
---
