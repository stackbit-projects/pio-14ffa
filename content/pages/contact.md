---
title: Contact me
hide_title: false
sections:
  - section_id: contact-form
    type: section_form
    content: To get in touch please fill the form below.
    form_id: contactForm
    form_action: /thank-you
    form_fields:
      - input_type: text
        name: name
        label: Name
        default_value: What is your name
        is_required: true
      - input_type: checkbox
        name: isACompany
        label: >-
          I'm a company
        is_required: true
      - input_type: select
        name: subject
        label: Subject
        default_value: Please select
        options:
          - Labor proposal
          - Website Feedback
          - Send me a greeting
          - Report a bug
          - Other
        is_required: true
      - input_type: email
        name: email
        label: Email
        default_value: Your email address
        is_required: true
     
      - input_type: textarea
        name: message
        label: Message
        default_value: Your message
        is_required: true
      - input_type: checkbox
        name: consent
        label: >-
          I understand that this form is storing my submitted information so I
          can be contacted.

    submit_label: Send Message
seo:
  title: Contact
  description: This is the contact page
  extra:
    - name: 'og:type'
      value: website
      keyName: property
    - name: 'og:title'
      value: Contact
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
layout: advanced
---
