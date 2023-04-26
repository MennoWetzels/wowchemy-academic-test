---
# Leave the homepage title empty to use the site title
title:
date: 2023-04-16
type: landing

sections:
  - block: about
    id: about
    content:
      title: Biography
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin

  - block: contact
    id: contact
    content:
      title: Contact
      # Contact (add or remove contact options as necessary)
      email: test@example.org
      address:
        street: André Severinweg 2C
        city: Maastricht
        postcode: '6214PM'
        country: The Netherlands
        country_code: NL
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
    design:
      columns: '2'
---
