name: Denylist Request
description: Report missing blockable domain(s).
labels: ["deny"]
assignees: 
  - Byteintosh
body:
  - type: textarea
    id: domains
    attributes:
      label: Which domain(s) should be blocked?
      description: |
        NOTE: Manually adding phishing domains is not really worthwhile, they are offline faster than they are on the list. If they exist for longer, they are automatically taken over by the next update via used phishing feeds.
    validations:
      required: true
  
  - type: textarea
    id: reason
    attributes:
      label: Why should these domain(s) be blocked?
      description: |
        If possible, please name the list versions in which the domain(s) should be blocked.
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