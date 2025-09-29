---
name: OSS Wishlist Request
about: Submit a request for open source project support
title: ''
labels: wishlist
assignees: emmairwin

---

title: "[Wishlist] "
labels: ["wishlist"]
body:
  - type: input
    id: project-title
    attributes:
      label: Project Title
      placeholder: "e.g., my-awesome-project"
    validations:
      required: true
  - type: input
    id: maintainer
    attributes:
      label: Maintainer GitHub Username
      placeholder: "@username"
    validations:
      required: true
  - type: checkboxes
    id: services
    attributes:
      label: Services Requested
      options:
        - label: Security Audit
        - label: Governance Setup
        - label: Legal Consultation
        - label: Funding Strategy
