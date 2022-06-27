---
widget: contact
headless: true  # This file represents a page section.

# ... Put Your Section Options Here (title etc.) ...
title: Contatti
subtitle: ''
weight: 100

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
  email: settignanocdp@gmail.com
  phone: 055 697007
  address:
    street: via San Romano 1
    city: Firenze
#    region: FI
    postcode: '50135'
    country: Italia
    country_code: IT
  coordinates:
    latitude: '43.7831028'
    longitude: '11.3215723'
  # directions: Enter Building 1 and take the stairs to Office 200 on Floor 2
#  office_hours:
#    - 'Monday 10:00 to 13:00'
#    - 'Wednesday 09:00 to 10:00'
#  appointment_url: 'https://calendly.com'
  contact_links:
    - icon: newspaper
      icon_pack: fas
      name: Newsletter
      link: https://cdp.settignano.org/newsletter/
    - icon: facebook
      icon_pack: fab
      name: Facebook
      link: https://www.facebook.com/settignanocdp
    - icon: instagram
      icon_pack: fab
      name: Instagram
      link: https://www.instagram.com/cdpsettignano/
    - icon: github
      icon_pack: fab
      name: GitHub
      link: https://github.com/settignano

design:
  # Choose how many columns the section has. Valid values: '1' or '2'.
  columns: '2'
---