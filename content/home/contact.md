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
  email: test@example.org
  phone: ""
  address:
    street: Avenida Lircay s/n, campus Talca
    city: ""
    region: ""
    postcode: '3480094'
    country: Chile
    country_code: CL
  coordinates:
    latitude: '-35.405166'
    longitude: '-71.633733'
  directions: Al costado del Centro de Estudios en Alimentos Procesados (CEAP)
#  office_hours:
 #   - ''
  #  - ''
  appointment_url:
  contact_links:
  

design:
  columns: '2'
---
