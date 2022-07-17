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
  email: samuel.holt.direct@gmail.com
  # phone: 
  address:
    street: Computational Mathematical Sciences, Wilberforce road
    city: Cambridge
    region: Cambridgeshire
    # postcode: '94305'
    country: United Kingdom
    country_code: UK
  coordinates:
    latitude: '37.4275'
    longitude: '-122.1697'
  directions: CMS reception
  office_hours:
    - 'Monday 10:00 to 18:00'
    - 'Tuesday 10:00 to 18:00'
    - 'Wednesday 10:00 to 18:00'
    - 'Thursday 10:00 to 18:00'
    - 'Friday 10:00 to 18:00'
  appointment_url: 'https://calendly.com'
  contact_links:
    - icon: twitter
      icon_pack: fab
      name: DM Me
      link: 'https://twitter.com/samianholt'
    - icon: video
      icon_pack: fas
      name: Zoom Me
      link: 'https://zoom.com'

design:
  columns: '2'
---
