name: 🐞 Bug report
description: Create a bug report to help us fix it
title: "bug report"
labels: [bug]
body:
  - type: checkboxes
    attributes:
      label: Is there an existing issue for this?
      description: Please search to see if an issue already exists for the bug you encountered.
      options:
        - label: I have searched the existing issues
          required: true
  - type: textarea
    attributes:
      label: Describe the bug
      description: A clear and concise description of what the bug is. Include images if relevant.
      placeholder: I accidentally deleted the internet. Here's my story ...
    validations:
      required: true
  - type: textarea
    attributes:
      label: Screenshots
      description: |
        Add screenshots to help explain your problem. You can also add a video here.

        Tip: You can attach images or video files by clicking this area to highlight it and then dragging files in.
    validations:
      required: false
  - type: textarea
    attributes:
      label: Steps To Reproduce
      description: Steps to reproduce the bug.
      placeholder: |
        1. Go to '...'
        2. Click on '...'
        3. Scroll to '...'
        4. See error
    validations:
      required: true
  - type: textarea
    attributes:
      label: Expected behavior
      description: A clear and concise description of what you expected to happen
    validations:
      required: true
  - type: textarea
    attributes:
      label: Logs
      description: If applicable, add your browser's console logs here
  - type: textarea
    attributes:
      label: Device information
      placeholder: |
        - OS: [e.g. Windows]
        - Browser: [e.g. chrome, safari, firefox]
        - Browser Version: [e.g. 22]
    validations:
      required: false
  - type: textarea
    attributes:
      label: Additional context
      description: |
        Do you have links to discussions about this on SN or other references?
    validations:
      required: false