name: Bug report
description: Create a report to help us improve
title: ''
labels: ["bug", "triage"]
assignees:
  - YurgFS
body:
  - type: markdown
    attributes:
      value: |
        Thanks for taking the time to fill out this bug report!
  - type: textarea
    id: what-happened
    attributes:
      label: Describe the bug
      description: A clear and concise description of what the bug is.
      render: Markdown
    validations:
      required: true
  - type: textarea
    id: to-reproduce
    attributes:
      label: To Reproduce
      description: Steps to reproduce the behavior.
      render: Markdown
    validations:
      required: true
  - type: textarea
    id: expected-behavior
    attributes:
      label: Expected behavior
      description: A clear and concise description of what you expected to happen.
      render: Markdown
    validations:
      required: true
  - type: textarea
    id: screenshots
    attributes:
      label: Screenshots
      description: If applicable, add screenshots to help explain your problem.
      render: Markdown
    validations:
      required: false
  - type: textarea
    id: logs
    attributes:
      label: Log file
      description: If applicable, add the part of the game log file to help explain your problem.
      render: Shell
    validations:
      required: false
  - type: textarea
    id: additional-context
    attributes:
      label: Additional context
      description: Add any other context about the problem here.
      render: Markdown
    validations:
      required: false
