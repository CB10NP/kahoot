name: Community Feedback Survey
description: Submit your feedback or feature suggestions directly to the project.
title: "[Survey]: "
labels: ["feedback"]
body:
  - type: markdown
    attributes:
      value: |
        Thanks for taking the time to share your feedback with us!
  - type: dropdown
    id: role
    attributes:
      label: What is your primary role?
      options:
        - Student / Player
        - Teacher / Host
        - Developer
        - Other
    validations:
      required: true
  - type: checkboxes
    id: features
    attributes:
      label: Which areas do you use the most?
      options:
        - label: Bot Control UI Overlay
        - label: Name Randomizer / Shuffler
        - label: Delay / Speed Configurations
  - type: textarea
    id: improvement
    attributes:
      label: What features should we build next?
      placeholder: Tell us what you want to see changed or added...
    validations:
      required: true
