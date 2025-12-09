name: Bug Report
description: Report a reproducible issue in the app.
title: "[BUG] "
labels: ["bug"]
body:
  - type: input
    id: device
    attributes:
      label: Device & OS
      placeholder: e.g., iPhone 14 / Android 12 / Windows 11
  - type: input
    id: app-version
    attributes:
      label: App Version
      placeholder: Found in app settings
  - type: textarea
    id: steps
    attributes:
      label: Steps to Reproduce
      placeholder: "1. Open app\n2. Tap X\n3. Crash occurs"
  - type: textarea
    id: expected
    attributes:
      label: Expected Behavior
  - type: textarea
    id: actual
    attributes:
      label: Actual Behavior
  - type: textarea
    id: media
    attributes:
      label: Screenshots / Video
      description: Upload files if applicable.
  - type: textarea
    id: notes
    attributes:
      label: Additional Notes
