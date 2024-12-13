---
name: Feature Request
about: Suggest a new feature for the project
title: "Feature: "
body:
  - type: input
    id: contact
    attributes:
      label: Contact Details
      description: What is your name?
      placeholder: ex. Aphichaya Suppakitkumjorn
      validations:
        required: true
  - type: markdown
    attributes:
      value: |
        Thanks for taking the time to fill out this feature request!
  - type: dropdown
    id: request-type
    attributes:
      label: Type of request?
      description: Select the type of your request
      options:
        - New Feature
        - Improvement
        - Other
      validations:
        required: true
  - type: dropdown
    id: os
    attributes:
      label: What is the OS which you want to suggest?
      description: Selections
      options:
        - Firefox
        - Chrome
        - Safari
        - Microsoft Edge
      validations:
        required: true
  - type: textarea
    id: details
    attributes:
      label: What are the details of your suggestion?
      description: Explain what you want
      placeholder: Feature details!
      validations:
        required: true

---


