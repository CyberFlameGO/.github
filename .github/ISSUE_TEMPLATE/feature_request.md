name: Request a feature
description: Make a suggestion for a new feature/suggest alternate functionality of something
labels:
  - content
body:
  - type: checkboxes
    attributes:
      label: Code of Conduct
      description: By submitting this issue, you agree to follow our [Code of Conduct](https://example.com)
      options:
        - label: I agree to follow this project's Code of Conduct
          required: true

  - type: textarea
    attributes:
      label: For minor changes, what files would be affected?
      description: |
        Include links to files if possible
    validations:
      required: false

  - type: textarea
    attributes:
      label: What changes are you suggesting?
      description: |
        - Give as much detail as you can to help us understand the change you want to see. 
        - Why should this be changed? What use cases does it support? 
        - What is the expected outcome?
    validations:
      required: true

  - type: textarea
    attributes:
      label: Additional information
      description: |
        Any additional information, configuration, or data that might be necessary to reproduce the issue.
    validations:
      required: false
