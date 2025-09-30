name: OSS Wishlist Request
description: Submit a request for open source project support
title: "[Wishlist] "
labels: ["wishlist"]
assignees: []
body:
  - type: markdown
    attributes:
      value: |
        Thanks for submitting an OSS Wishlist request! Please fill out the information below.
  
  - type: input
    id: project-title
    attributes:
      label: Project Title
      description: The name of your open source project
      placeholder: "e.g., my-awesome-library"
    validations:
      required: true
  
  - type: input
    id: project-url
    attributes:
      label: Project Repository URL
      description: Link to your project's GitHub repository
      placeholder: "https://github.com/username/project"
    validations:
      required: false
  
  - type: input
    id: maintainer
    attributes:
      label: Maintainer GitHub Username
      description: Your GitHub username (without the @)
      placeholder: "username"
    validations:
      required: true
  
  - type: checkboxes
    id: services
    attributes:
      label: Services Requested
      description: What services are you looking for? (Select all that apply)
      options:
        - label: Security Audit
        - label: Dependency Security Audit  
        - label: Governance Setup
        - label: Project Governance Setup
        - label: Legal Consultation
        - label: Stakeholder Mediation
        - label: Funding Strategy
    validations:
      required: true
  
  - type: dropdown
    id: urgency
    attributes:
      label: Urgency Level
      description: How urgent is this request?
      options:
        - Low
        - Medium
        - High
        - Critical
      default: 0
    validations:
      required: true
  
  - type: textarea
    id: description
    attributes:
      label: Project Description
      description: Brief description of your project and its goals
      placeholder: "Tell us about your project..."
    validations:
      required: true
  
  - type: textarea
    id: context
    attributes:
      label: Additional Context
      description: Any additional information that would help us understand your needs
      placeholder: "Any other details..."
    validations:
      required: false
