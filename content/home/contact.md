---
# An instance of the Contact widget.
widget: contact

# This file represents a page section.
headless: true

# Order that this section appears on the page.
weight: 130

title: Contacto
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
  phone: 888 888 88 88
  address:
    street: Ruta 118, Talca, Maule, Chile
    city: Talca
    region: Región del Maule
    postcode: '3480094'
    country: Chile
    country_code: CL
  coordinates:
    latitude: '-35.405184'
    longitude: '-71.633775' 
  directions: Centro ubicado a un costado del CEAP, frente a jardín botanico
  office_hours:
    - 'Lunes 10:00 to 13:00'
    - 'Viernes 09:00 to 10:00'
  appointment_url: 'https://calendly.com'
  
design:
  columns: '2'
---
