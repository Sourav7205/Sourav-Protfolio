name: Portfolio Feedback
description: Provide feedback or suggestions for improvement.
title: "[Feedback]: "
labels: ["enhancement", "feedback"]
assignees: []
body:
  - type: markdown
    attributes:
      value: |
        Thank you for visiting my portfolio! Your feedback is invaluable in helping me improve and grow. Please fill out the following sections to provide your insights.
  - type: input
    id: name
    attributes:
      label: Your Name
      description: Please provide your full name.
      placeholder: e.g., John Doe
    validations:
      required: true
  - type: input
    id: email
    attributes:
      label: Your Email
      description: Optional. Provide your email if you'd like a response.
      placeholder: e.g., john.doe@example.com
    validations:
      required: false
  - type: textarea
    id: feedback
    attributes:
      label: Your Feedback
      description: Share your thoughts, suggestions, or any issues you encountered.
      placeholder: e.g., The website's navigation could be more intuitive.
    validations:
      required: true
  - type: checkboxes
    id: consent
    attributes:
      label: Consent
      description: By submitting this form, you agree to allow me to use your feedback for improvement purposes.
      options:
        - label: I agree to provide feedback
          required: true
