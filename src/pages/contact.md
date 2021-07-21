---
title: Let's Talk
hide_title: false
sections:
  - section_id: contact-form
    type: section_form
    content: >
      Hola! Want to reach out and connect? Please fill the contact form below
      and I'll get back to you asap. Alternatively, I can be reached via
      [LinkedIn](https://www.linkedin.com/in/holaphil/) or here on
      [Twitter](https://twitter.com/holaphil).
    form_id: contactForm
    form_action: /thank-you
    form_fields:
      - input_type: text
        name: name
        label: Name
        default_value: Your name
        is_required: true
      - input_type: email
        name: email
        label: Email
        default_value: Your email address
        is_required: true
      - input_type: select
        name: subject
        label: Subject
        default_value: Please select
        options:
          - Error on the site
          - Sponsorship
          - Other
      - input_type: textarea
        name: message
        label: Message
        default_value: Your message
      - input_type: checkbox
        name: consent
        label: >-
          I understand that this form is storing my submitted information so I
          can be contacted.
    submit_label: Send Message
seo:
  title: Phil Thomas DiGiulio / Contact
  description: >-
    Hola! Want to reach out and connect? Please fill the contact form below and
    I'll get back to you asap. Alternatively, DM me via LinkedIn or Twitter.
  extra:
    - name: 'og:type'
      value: website
      keyName: property
    - name: 'og:title'
      value: Phil Thomas DiGiulio / Contact
      keyName: property
    - name: 'og:description'
      value: This is the contact page
      keyName: property
    - name: 'twitter:card'
      value: summary
    - name: 'twitter:title'
      value: Contact
    - name: 'twitter:description'
      value: This is the contact page
template: advanced
---
