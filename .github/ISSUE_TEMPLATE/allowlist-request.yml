name: Allowlist Request
description: Report incorrectly blocked domain(s).
labels: ["allow"]
assignees: 
  - Byteintosh
body:
  - type: textarea
    id: domains
    attributes:
      label: Which domain(s) should be unblocked?
    validations:
      required: true
  
  - type: textarea
    id: reason
    attributes:
      label: Why should the domain(s) be unblocked?
      description: |
        Provide as many details as possible to avoid unnecessary enquiries. If necessary, please describe the steps to reproduce. You can also add screenshots.
    validations:
      required: true

  - type: checkboxes
    id: terms
    attributes:
      label: Privacy
      description: By submitting this issue, you agree that the report will not contain any private information.
      options:
        - label: I confirm that the report does not contain any private information.
          required: true