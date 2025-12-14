name: Feature Request
description: 提出一个新功能或改进建议
labels: [enhancement]
body:
  - type: textarea
    id: summary
    attributes:
      label: 功能概述
    validations:
      required: true

  - type: textarea
    id: motivation
    attributes:
      label: 为什么需要这个功能？
    validations:
      required: true

  - type: textarea
    id: details
    attributes:
      label: 功能细节
