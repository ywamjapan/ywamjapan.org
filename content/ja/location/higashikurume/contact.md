---
# An instance of the Contact widget.
# Documentation: https://sourcethemes.com/academic/docs/page-builder/
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
      captcha: true

  oploc:
    website: https://ywamtokyo.org
    email:  info@ywamtokyo.org
    # phone: 888 888 88 88
    address:
      # street: 新川町1-17-7
      city: 東久留米市
      region: 東京都
      # postcode: 〒203-0013
      country: 日本
      country_code: JP
    coordinates:
      latitude: 35.758914
      longitude: 139.538747

design:
  columns: '2'
---