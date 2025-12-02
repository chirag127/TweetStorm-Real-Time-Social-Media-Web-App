---
name: Bug Report
about: Report an issue with StreamSphere
title: "BUG: "
labels: "bug"
assignees:

body:
  - type: markdown
    attributes:
      value: | # IMPORTANT: All links must use the new repository name!
        Please provide a clear and concise description of the bug.
        
        **Repository Link:** https://github.com/chirag127/StreamSphere-Real-Time-Social-Platform-React-Template
        
        Thank you for helping improve StreamSphere!

  - type: input
    id: browser
    name: Browser & Version
    attributes:
      label: Which browser are you using?
      description: Please specify the browser and its version (e.g., Chrome 126, Firefox 120).
      placeholder: "e.g. Chrome 126"
    validations:
      required: true

  - type: input
    id: os
    name: Operating System
    attributes:
      label: What OS are you using?
      description: Please specify the operating system (e.g., Windows 11, macOS Sonoma, Ubuntu 22.04).
      placeholder: "e.g. Windows 11"
    validations:
      required: true

  - type: textarea
    id: steps
    name: Steps to Reproduce
    attributes:
      label: Steps to reproduce the behavior:
      description: Provide a clear sequence of steps that will reproduce the bug.
      placeholder: |
        1. Go to '/some-page'
        2. Click on the 'Button'
        3. Observe the error...
    validations:
      required: true

  - type: textarea
    id: expected_behavior
    name: Expected Behavior
    attributes:
      label: What did you expect to happen?
      description: Describe what you expected to occur.
      placeholder: "The UI should update to show the new data."
    validations:
      required: true

  - type: textarea
    id: actual_behavior
    name: Actual Behavior
    attributes:
      label: What actually happened?
      description: Describe what actually occurred, and include any error messages.
      placeholder: "The UI remained unchanged, and a JavaScript error appeared in the console."
    validations:
      required: true

  - type: textarea
    id: additional_context
    name: Additional Context
    attributes:
      label: Add any other context about the problem here.
      description: |
        Screenshots, logs, relevant configuration files, or links to related issues.
        Remember to use the correct repository link: https://github.com/chirag127/StreamSphere-Real-Time-Social-Platform-React-Template
      placeholder: "e.g. Attached screenshot shows the error in the browser console."
    validations:
      required: false

  - type: markdown
    attributes:
      value: | # IMPORTANT: All links must use the new repository name!
        ### Technical Stack
        
        - **Repository:** https://github.com/chirag127/StreamSphere-Real-Time-Social-Platform-React-Template
        - **Language:** JavaScript
        - **Frontend Framework:** React 19+
        - **Build Tool:** Vite 7+
        - **Styling:** TailwindCSS v4+
        - **Runtime:** Node.js 20+
        - **Testing Framework:** Vitest, Playwright
        
        For more details on the Apex Toolchain and architectural principles, please refer to the [AGENTS.md](https://github.com/chirag127/StreamSphere-Real-Time-Social-Platform-React-Template/blob/main/AGENTS.md) file.
